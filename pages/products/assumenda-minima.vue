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
      return {"slug":"assumenda-minima","name":"Assumenda velit provident et.","description":"Amet harum provident. Est quo qui. Odit modi dolorem.","price":54041.96,"header":"Itaque quas inventore quia.","footer":"Voluptatem eos reiciendis eum.","moreInfo":"Incidunt et et animi."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
