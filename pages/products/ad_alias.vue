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
      return {"slug":"ad_alias","name":"Autem in et dolorum.","description":"Expedita ratione doloribus. Quo et ratione. Eius deserunt et.","price":28999.01,"header":"Nam aut aut natus.","footer":"Ea quia ut aut.","moreInfo":"Dolorum ipsa ea enim."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
