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
      return {"slug":"soluta_voluptatem","name":"Cupiditate voluptatem dolor molestias.","description":"Autem non debitis. Nemo sequi quis. Qui dolorem dignissimos.","price":25723.19,"header":"Quisquam tempore optio iusto.","footer":"Sit facere saepe consequatur.","moreInfo":"Sunt nulla facere et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
