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
      return {"slug":"officia-explicabo","name":"Culpa voluptates quasi libero.","description":"Tempore excepturi ut. Similique velit sed. Sunt quo occaecati.","price":42573.15,"header":"Consequatur est voluptatem fugit.","footer":"Possimus omnis eum ut.","moreInfo":"Optio fugit perspiciatis consequatur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
