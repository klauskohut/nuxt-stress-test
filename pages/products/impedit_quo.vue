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
      return {"slug":"impedit_quo","name":"Minus maiores quibusdam dolor.","description":"Ut occaecati ratione. Quas reprehenderit sed. Id sed non.","price":32346.68,"header":"Totam voluptatem iure quis.","footer":"Nulla ut laborum sit.","moreInfo":"Cumque tempora molestias similique."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
