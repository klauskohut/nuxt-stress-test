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
      return {"slug":"saepe_possimus","name":"Deserunt non sed necessitatibus.","description":"Voluptates facere recusandae. Dolorum sed et. Ab cumque sint.","price":49896.89,"header":"In molestiae sint optio.","footer":"Ex rerum et et.","moreInfo":"Tenetur maiores voluptatem sed."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
