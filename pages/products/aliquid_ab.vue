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
      return {"slug":"aliquid_ab","name":"Non dolorum excepturi voluptas.","description":"Modi tempore vitae. Mollitia explicabo molestias. Est sapiente est.","price":56800.76,"header":"Doloremque iste consequuntur inventore.","footer":"Voluptatibus et ut qui.","moreInfo":"Rerum sed eum ipsam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
