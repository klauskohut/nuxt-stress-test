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
      return {"slug":"qui-nihil","name":"A omnis sapiente et.","description":"Eligendi dolores fuga. Placeat voluptas dolorem. Est aut hic.","price":53018.27,"header":"Commodi consequatur sit et.","footer":"Magnam distinctio soluta quo.","moreInfo":"Necessitatibus corporis odio architecto."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
