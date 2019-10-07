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
      return {"slug":"excepturi-rerum","name":"Ex provident quis sequi.","description":"Necessitatibus optio harum. Et est aut. Officia ut consequatur.","price":62071.08,"header":"Sunt at doloribus corporis.","footer":"Quia quis animi et.","moreInfo":"Nam qui velit nobis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
