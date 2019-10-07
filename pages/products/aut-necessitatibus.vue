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
      return {"slug":"aut-necessitatibus","name":"Aut iure dolor consequatur.","description":"Occaecati velit impedit. Qui et eos. Consequatur ut aperiam.","price":39632.78,"header":"Quia id aliquid et.","footer":"Minus ipsum est perspiciatis.","moreInfo":"Placeat nihil dolore laudantium."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
