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
      return {"slug":"expedita_aut","name":"Cupiditate perspiciatis sed laudantium.","description":"Ad fugit minus. Qui explicabo enim. Possimus est omnis.","price":66806.55,"header":"Quibusdam ipsum eligendi tenetur.","footer":"Aut qui dicta ratione.","moreInfo":"Enim necessitatibus voluptatibus natus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
