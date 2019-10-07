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
      return {"slug":"quis_soluta","name":"Architecto esse dolores dolorem.","description":"Odio doloremque consequatur. Eos maxime quae. Aut harum debitis.","price":28736.89,"header":"Tenetur ea et aspernatur.","footer":"Sint ipsa et amet.","moreInfo":"Qui quis aspernatur dignissimos."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
