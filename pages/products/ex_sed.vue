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
      return {"slug":"ex_sed","name":"Ut corporis rerum et.","description":"Voluptates quis deleniti. Et esse et. Eius ea ipsum.","price":31943.22,"header":"Sed laboriosam ea voluptas.","footer":"Officiis aperiam sit et.","moreInfo":"Blanditiis laboriosam in nulla."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
