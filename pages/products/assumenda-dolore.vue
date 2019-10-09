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
      return {"slug":"assumenda-dolore","name":"Perspiciatis dolor et adipisci.","description":"Temporibus aut est. Non facere placeat. Suscipit rerum debitis.","price":40571.92,"header":"Ut vero magnam consequatur.","footer":"Vero blanditiis labore perferendis.","moreInfo":"Illum facere qui eaque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
