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
      return {"slug":"repudiandae-omnis","name":"Debitis sed aut quibusdam.","description":"Fugiat eum voluptate. Consectetur eos aperiam. Sint cum dolor.","price":15576.59,"header":"Non eius quis eveniet.","footer":"Minus fugit est unde.","moreInfo":"Dolorem numquam et quia."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
