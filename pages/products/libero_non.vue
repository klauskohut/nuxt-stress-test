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
      return {"slug":"libero_non","name":"Sunt odio ut deserunt.","description":"Est et et. Ratione tenetur doloribus. Quia amet eum.","price":94233.28,"header":"Sapiente consectetur iste ad.","footer":"Quae iusto quos qui.","moreInfo":"Eum veniam voluptatem omnis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
