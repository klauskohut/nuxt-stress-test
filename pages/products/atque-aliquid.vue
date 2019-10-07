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
      return {"slug":"atque-aliquid","name":"Est dolor atque voluptates.","description":"Reprehenderit in tempore. Et labore ab. Provident minima dolore.","price":54278.06,"header":"Dolores nobis eveniet qui.","footer":"Delectus ut ab natus.","moreInfo":"Consectetur dignissimos aut numquam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
