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
      return {"slug":"maiores_non","name":"Alias ut beatae qui.","description":"Doloribus voluptatum dolorem. Voluptatem et tempora. Qui fugit ratione.","price":12570.26,"header":"Qui aliquid quae quam.","footer":"Quaerat qui eos vitae.","moreInfo":"Et quis voluptatem ea."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
