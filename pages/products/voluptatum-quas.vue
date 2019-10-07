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
      return {"slug":"voluptatum-quas","name":"Ut eum minus porro.","description":"Cupiditate temporibus iusto. Ipsam odit laborum. Qui tempora sed.","price":51239.74,"header":"Aut ad exercitationem qui.","footer":"Quas voluptatem et nisi.","moreInfo":"Distinctio modi ad placeat."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
