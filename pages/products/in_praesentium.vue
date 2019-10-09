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
      return {"slug":"in_praesentium","name":"Non minima possimus enim.","description":"Dolores amet cum. In quo perferendis. Dicta officiis velit.","price":82785.23,"header":"Et minus illo consequatur.","footer":"Ad ullam numquam consequuntur.","moreInfo":"Consequatur voluptatibus necessitatibus laudantium."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
