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
      return {"slug":"possimus_omnis","name":"Atque id non enim.","description":"Possimus qui libero. Aut corporis enim. Aliquid doloremque aut.","price":52059.52,"header":"Magni libero et nam.","footer":"Quae nisi qui rerum.","moreInfo":"Cumque voluptatem totam nulla."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
