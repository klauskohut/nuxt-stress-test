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
      return {"slug":"ut-id","name":"Voluptatum qui assumenda voluptate.","description":"Soluta aperiam et. Vitae consequatur et. Eaque minima aut.","price":14701.17,"header":"Eum voluptates deleniti recusandae.","footer":"Quis dolor est beatae.","moreInfo":"Aliquid culpa dolorem aut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
