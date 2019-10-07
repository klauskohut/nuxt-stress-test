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
      return {"slug":"odio-dignissimos","name":"Est et repellendus consequatur.","description":"Odio dolores aspernatur. Iste aliquam praesentium. Magni eum in.","price":62418.57,"header":"Culpa odit cupiditate quaerat.","footer":"Quia vitae rerum quis.","moreInfo":"Minus ex quisquam enim."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
