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
      return {"slug":"rerum-autem","name":"Accusantium delectus qui voluptatum.","description":"Autem vel sed. Qui in vero. Saepe aliquid sed.","price":56237.49,"header":"Temporibus adipisci ut velit.","footer":"Quam eos et pariatur.","moreInfo":"Molestias et aliquid nihil."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
