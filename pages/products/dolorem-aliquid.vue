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
      return {"slug":"dolorem-aliquid","name":"Excepturi dolor ad blanditiis.","description":"Sit odit enim. Sunt sunt maiores. Ipsum ipsa rerum.","price":68359.47,"header":"Et ut totam maxime.","footer":"Sint enim neque explicabo.","moreInfo":"Qui distinctio eaque explicabo."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
