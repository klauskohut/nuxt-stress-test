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
      return {"slug":"quia_adipisci","name":"Quo rem corrupti sint.","description":"Delectus dolorum voluptatem. Aut veniam dignissimos. Explicabo laborum aut.","price":79911.61,"header":"Quia et consequuntur deserunt.","footer":"Atque alias ipsum minus.","moreInfo":"Ipsam consequuntur porro dolorem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
