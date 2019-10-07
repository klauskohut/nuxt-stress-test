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
      return {"slug":"officia_dolores","name":"Fugiat aliquid atque tenetur.","description":"Sit dolor ab. Reiciendis et aut. Modi aperiam et.","price":85696.83,"header":"Et quo et molestiae.","footer":"Neque magni quia assumenda.","moreInfo":"Tempore neque hic aut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
