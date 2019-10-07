<template>
  <Product :slug="slug" :name="name" :description="description" :price="price" :header="header" :footer="footer">
    <h3>More product info below:</h3>
    <p>{{moreInfo}}</p>
  </Product>
</template>

<script>
  import Product from '../product'
  export default {
    layout: 'product',
    components: {
      Product,
    },
    data() {
      return {"slug":"facilis-iusto","name":"Omnis laboriosam accusantium voluptatem.","description":"Nemo mollitia quis. Quam maxime et. Id dolores consequatur.","price":21512.26,"header":"Et eos dolorem ipsa.","footer":"Culpa quibusdam et et.","moreInfo":"Facilis consectetur quia aliquid."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
