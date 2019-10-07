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
      return {"slug":"temporibus_molestias","name":"Dolorem hic maxime aut.","description":"Eaque dicta quae. Excepturi omnis nobis. Occaecati sit quas.","price":88730.84,"header":"Reiciendis ratione voluptatem excepturi.","footer":"Aspernatur officia ipsum nulla.","moreInfo":"Quia vel est unde."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
