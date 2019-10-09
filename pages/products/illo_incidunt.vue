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
      return {"slug":"illo_incidunt","name":"Facilis exercitationem maiores incidunt.","description":"Non consectetur quia. Qui molestias est. Corrupti dolores pariatur.","price":99101.63,"header":"Sit quae incidunt iusto.","footer":"Voluptatibus rem qui dolore.","moreInfo":"Quo iusto iste temporibus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
