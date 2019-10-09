<template>
  <Product :slug="slug" :name="name" :description="description" :price="price" :header="header" :footer="footer">
    <Slider />
    <h3>More product info below:</h3>
    <p>{{moreInfo}}</p>
  </Product>
</template>

<script>
  import Product from '../product'
  import Slider from '../../components/Slider'

  export default {
    layout: 'product',
    components: {
      Product,
      Slider
    },
    data() {
      return {"slug":"tenetur-minima","name":"Facilis esse dolor ea.","description":"Optio delectus quasi. Laudantium iste voluptas. Fugiat velit pariatur.","price":41405.04,"header":"Iure ullam animi nostrum.","footer":"Consequatur quo quam ratione.","moreInfo":"Consequatur fugit quo doloremque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
