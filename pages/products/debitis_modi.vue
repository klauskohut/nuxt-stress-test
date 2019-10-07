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
      return {"slug":"debitis_modi","name":"Incidunt odio sit repellendus.","description":"Sit quia quibusdam. Explicabo ut tempore. Dolor voluptas sed.","price":17154.76,"header":"Expedita dolorem a pariatur.","footer":"Doloremque et hic quasi.","moreInfo":"Ut amet dignissimos harum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
