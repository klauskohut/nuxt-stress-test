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
      return {"slug":"consequuntur_nostrum","name":"Est excepturi rem eligendi.","description":"Ullam ipsam esse. Sunt expedita illum. Ducimus quis sit.","price":66284.61,"header":"Voluptas eum maxime temporibus.","footer":"In fuga totam rerum.","moreInfo":"Cumque aliquid accusamus necessitatibus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
