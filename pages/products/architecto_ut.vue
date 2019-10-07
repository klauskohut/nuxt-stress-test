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
      return {"slug":"architecto_ut","name":"Reprehenderit vero ut cupiditate.","description":"Saepe excepturi doloremque. Quaerat ab fugiat. Laudantium reiciendis consequatur.","price":83378.27,"header":"Sunt provident aliquam ea.","footer":"Occaecati minima accusamus tempora.","moreInfo":"Non blanditiis quia quam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
