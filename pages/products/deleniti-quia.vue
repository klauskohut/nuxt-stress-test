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
      return {"slug":"deleniti-quia","name":"Blanditiis voluptatum porro suscipit.","description":"Illum dolorum voluptatem. Rerum voluptas officiis. Aut dolorem facilis.","price":70795.36,"header":"Doloribus dicta non odit.","footer":"Eligendi temporibus est vel.","moreInfo":"Aut iure tempore inventore."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
