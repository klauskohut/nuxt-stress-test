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
      return {"slug":"est-reprehenderit","name":"Sint dolorum ea porro.","description":"Itaque delectus praesentium. Eligendi omnis saepe. Labore iusto et.","price":64159.11,"header":"Consectetur totam facere id.","footer":"Earum excepturi quo consequatur.","moreInfo":"Voluptas rerum ut velit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
