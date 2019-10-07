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
      return {"slug":"quaerat_sapiente","name":"Minus tenetur aut error.","description":"Quod qui odit. Facere sit libero. Temporibus ab deserunt.","price":69133.98,"header":"Laborum architecto aspernatur blanditiis.","footer":"Amet voluptatum aut autem.","moreInfo":"Quod voluptatem corrupti assumenda."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
