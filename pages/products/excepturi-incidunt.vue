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
      return {"slug":"excepturi-incidunt","name":"Sit iure ut voluptas.","description":"Voluptatem fugit consequatur. Quibusdam iste eveniet. Porro ut qui.","price":36493.49,"header":"Libero magnam rerum voluptatem.","footer":"Magni vel necessitatibus expedita.","moreInfo":"Velit nihil vel deserunt."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
