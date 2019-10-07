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
      return {"slug":"nihil-accusamus","name":"Id ut aut ut.","description":"Quae fuga corporis. Veniam unde nihil. Voluptatem velit vel.","price":71313.85,"header":"Ducimus sunt hic repudiandae.","footer":"Modi alias odio soluta.","moreInfo":"Dolorem error et consequatur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
