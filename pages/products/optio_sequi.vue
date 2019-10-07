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
      return {"slug":"optio_sequi","name":"Officiis unde quo excepturi.","description":"Eligendi illum corporis. Ab vero et. Facere eum dolores.","price":93689.85,"header":"Et nisi sit enim.","footer":"Dolorem nesciunt at vel.","moreInfo":"Iusto provident assumenda animi."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
