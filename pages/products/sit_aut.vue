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
      return {"slug":"sit_aut","name":"Sit porro dolorum aliquid.","description":"Eum nihil dolorum. Ratione et et. Nam velit neque.","price":29585.54,"header":"Sunt fugiat ut eius.","footer":"Cumque illo et odio.","moreInfo":"Iste non qui dignissimos."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
