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
      return {"slug":"deserunt_dolorem","name":"Consequatur vel officiis ut.","description":"Accusamus sed architecto. Quisquam eius modi. Harum magni qui.","price":76323.77,"header":"Vitae est iure totam.","footer":"Est accusamus consequatur rerum.","moreInfo":"Facere laborum molestias et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
