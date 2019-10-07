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
      return {"slug":"perspiciatis-fugit","name":"Ipsam culpa ratione dolorem.","description":"Quo rerum dolor. Et enim ut. Cumque magnam saepe.","price":79776.41,"header":"Rem eaque voluptatem cum.","footer":"Ipsa impedit animi aut.","moreInfo":"Corporis quia ipsa placeat."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
