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
      return {"slug":"qui-facilis","name":"Molestiae dolorem illo minus.","description":"Aliquid rem inventore. Quibusdam non quos. Harum et sit.","price":52087.65,"header":"Alias quidem animi amet.","footer":"Omnis aliquid corporis maiores.","moreInfo":"Temporibus quo non id."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
