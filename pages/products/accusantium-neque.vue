<template>
  <Product :slug="slug" :name="name" :description="description" :price="price" :header="header" :footer="footer">
    <Slider />
    <h3>More product info below:</h3>
    <p>{{moreInfo}}</p>
  </Product>
</template>

<script>
  import Product from '../product'
  import Slider from '../../components/Slider'

  export default {
    layout: 'product',
    components: {
      Product,
      Slider
    },
    data() {
      return {"slug":"accusantium-neque","name":"Nam necessitatibus in non.","description":"Mollitia explicabo minus. Qui facilis exercitationem. Animi provident aspernatur.","price":57711.53,"header":"Non deleniti voluptatum praesentium.","footer":"Incidunt consectetur eaque aut.","moreInfo":"Molestias rerum ut consequatur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
