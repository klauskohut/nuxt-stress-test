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
      return {"slug":"dolorem-velit","name":"Blanditiis quaerat occaecati consequatur.","description":"Quia fuga quae. Cumque non voluptas. Mollitia qui sequi.","price":29102.96,"header":"Quo mollitia ex nemo.","footer":"Ea labore sed earum.","moreInfo":"Et rem autem animi."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
