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
      return {"slug":"accusamus-voluptas","name":"Aliquid voluptas sint modi.","description":"Ab ut eum. Cum aliquam eaque. Possimus eos suscipit.","price":23034.09,"header":"Eum rerum quisquam id.","footer":"Odio assumenda pariatur aut.","moreInfo":"Impedit corrupti et rerum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
