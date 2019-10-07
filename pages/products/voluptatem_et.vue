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
      return {"slug":"voluptatem_et","name":"Doloremque non architecto praesentium.","description":"Temporibus doloremque blanditiis. Asperiores laboriosam facilis. Fugit sed sit.","price":81133.06,"header":"Explicabo quis libero minus.","footer":"Dicta tempore molestias accusantium.","moreInfo":"Id quo optio nihil."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
