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
      return {"slug":"optio_ut","name":"Modi labore voluptates quisquam.","description":"Et est tenetur. Ea sed perferendis. Esse eum maxime.","price":45915.08,"header":"Sint iusto quia deserunt.","footer":"Eos qui voluptatum illum.","moreInfo":"Quo et odio ipsa."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
