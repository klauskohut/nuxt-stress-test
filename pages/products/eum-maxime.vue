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
      return {"slug":"eum-maxime","name":"Qui ut dolorum dicta.","description":"Modi recusandae aut. Culpa fuga magnam. Aliquam illum ea.","price":85138.17,"header":"Reprehenderit quos voluptas illo.","footer":"Totam vitae temporibus pariatur.","moreInfo":"Molestias officia voluptatem error."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
