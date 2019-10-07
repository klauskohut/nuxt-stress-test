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
      return {"slug":"molestiae_soluta","name":"Necessitatibus illo sit a.","description":"Officia dignissimos impedit. Distinctio numquam voluptatem. Odio non blanditiis.","price":98765.14,"header":"Alias autem voluptas enim.","footer":"Vel ab sequi omnis.","moreInfo":"Totam ipsa alias quis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
