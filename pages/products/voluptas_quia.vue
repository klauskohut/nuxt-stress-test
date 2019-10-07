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
      return {"slug":"voluptas_quia","name":"Qui quis voluptate enim.","description":"Veritatis sit pariatur. Magni ut qui. Fugit provident quisquam.","price":70285.13,"header":"Consequatur veritatis explicabo sit.","footer":"Ut soluta quaerat iste.","moreInfo":"Quo incidunt fuga vel."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
