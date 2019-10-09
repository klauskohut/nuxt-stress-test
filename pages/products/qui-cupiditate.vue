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
      return {"slug":"qui-cupiditate","name":"Animi ducimus quia sunt.","description":"Omnis magni enim. Harum in eligendi. Natus vitae velit.","price":74938.29,"header":"Error tempore sequi ullam.","footer":"Est blanditiis iusto error.","moreInfo":"Praesentium nulla consequatur sunt."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
