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
      return {"slug":"facere_sit","name":"Ea quae ut nulla.","description":"Illum et sunt. Blanditiis sed qui. Sit voluptatibus voluptatum.","price":24653.15,"header":"Suscipit voluptas sed maxime.","footer":"Reprehenderit similique magni pariatur.","moreInfo":"Ut fugit aut ut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
