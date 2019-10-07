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
      return {"slug":"et-fugit","name":"Ut id mollitia numquam.","description":"Nihil delectus earum. Qui veritatis animi. Quis modi aliquid.","price":82966.21,"header":"Consectetur est totam est.","footer":"Recusandae aperiam deserunt quam.","moreInfo":"Quidem laudantium qui dolorum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
