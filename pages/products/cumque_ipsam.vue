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
      return {"slug":"cumque_ipsam","name":"Et autem corporis repellat.","description":"Distinctio maxime eos. Libero ut tempore. Qui quaerat repellendus.","price":49605.88,"header":"Id pariatur incidunt ut.","footer":"Nam quis doloribus enim.","moreInfo":"In voluptatum cum consequatur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
