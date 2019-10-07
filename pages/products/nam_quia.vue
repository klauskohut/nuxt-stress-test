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
      return {"slug":"nam_quia","name":"In rerum debitis voluptatem.","description":"Et iure reiciendis. Molestiae quasi quidem. Sed quia debitis.","price":58831.84,"header":"Et aut nisi consequatur.","footer":"Similique ex sint earum.","moreInfo":"Consequatur dolorem accusantium optio."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
