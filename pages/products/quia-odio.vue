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
      return {"slug":"quia-odio","name":"Sit eum quasi porro.","description":"Temporibus illo qui. Harum enim ex. Totam et vel.","price":46660.96,"header":"Officiis deserunt illo distinctio.","footer":"Deserunt quia molestias eius.","moreInfo":"Dicta eos sapiente ad."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
