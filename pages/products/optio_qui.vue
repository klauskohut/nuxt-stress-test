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
      return {"slug":"optio_qui","name":"Hic eveniet repudiandae nihil.","description":"In explicabo adipisci. Fugiat aut sunt. Impedit nihil cum.","price":93397.26,"header":"Quisquam aut saepe est.","footer":"Aut assumenda adipisci rerum.","moreInfo":"Commodi est qui velit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
