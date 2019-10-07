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
      return {"slug":"quae-eum","name":"Expedita omnis quis voluptas.","description":"Voluptatem fuga expedita. Commodi a at. Tempore deleniti odit.","price":20789.93,"header":"Ipsam aut quaerat aliquam.","footer":"Fuga vel soluta rerum.","moreInfo":"Voluptates qui laboriosam rerum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
