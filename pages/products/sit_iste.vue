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
      return {"slug":"sit_iste","name":"Atque laudantium quas et.","description":"Voluptate ut eaque. Praesentium sint id. Vel earum id.","price":40682.47,"header":"Corporis qui porro voluptatem.","footer":"Autem dolores repellat minima.","moreInfo":"Dolores consectetur distinctio dignissimos."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
