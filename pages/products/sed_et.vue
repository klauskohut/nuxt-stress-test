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
      return {"slug":"sed_et","name":"Eius molestiae aut velit.","description":"Aliquid qui ut. Illum nihil tenetur. Doloribus et velit.","price":45803.37,"header":"Sed praesentium impedit maiores.","footer":"Cum corporis laborum sit.","moreInfo":"Non expedita ea vero."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
