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
      return {"slug":"qui_laudantium","name":"Expedita aut odit eveniet.","description":"Voluptatem distinctio est. Expedita fugiat voluptas. Aut voluptatem impedit.","price":63812.16,"header":"Id dolores saepe officia.","footer":"Quasi eveniet harum ab.","moreInfo":"Quisquam necessitatibus vitae id."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
