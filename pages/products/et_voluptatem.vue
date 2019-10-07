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
      return {"slug":"et_voluptatem","name":"Dolorum voluptatem dolores consequatur.","description":"Occaecati aut odit. Est qui consequatur. Non illum sed.","price":36253.77,"header":"Ad perferendis fugiat voluptas.","footer":"Vel perspiciatis nesciunt eum.","moreInfo":"Enim ullam dolor iste."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
