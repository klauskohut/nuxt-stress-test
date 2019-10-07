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
      return {"slug":"nemo_ea","name":"Et sint similique enim.","description":"Aliquam hic soluta. Nihil necessitatibus consectetur. Temporibus amet consequatur.","price":96977.68,"header":"Et tempora dolorum minima.","footer":"Omnis qui quibusdam saepe.","moreInfo":"Rem facilis aut occaecati."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
