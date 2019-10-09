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
      return {"slug":"beatae_autem","name":"Aut possimus esse non.","description":"Blanditiis molestias enim. Facere voluptatem distinctio. Aliquam voluptatem quis.","price":15192.52,"header":"Molestias officiis ducimus pariatur.","footer":"Praesentium et vero blanditiis.","moreInfo":"Ut voluptas rerum tempore."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
