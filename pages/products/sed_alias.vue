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
      return {"slug":"sed_alias","name":"Rerum iure officia consequatur.","description":"Qui et ut. Tempore tenetur maxime. Sed laborum est.","price":99174.19,"header":"Ab et nemo quas.","footer":"Porro minima cumque nostrum.","moreInfo":"Porro molestias ad et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
