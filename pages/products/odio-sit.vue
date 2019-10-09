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
      return {"slug":"odio-sit","name":"Facilis ad id ut.","description":"Qui mollitia repudiandae. Voluptas explicabo omnis. Autem rerum aspernatur.","price":44476.36,"header":"Fugit aut eligendi quia.","footer":"Hic adipisci delectus repudiandae.","moreInfo":"Sed hic quia dolores."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
