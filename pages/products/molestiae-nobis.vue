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
      return {"slug":"molestiae-nobis","name":"Corrupti ut et nemo.","description":"Enim saepe iste. Provident voluptates sequi. Nulla neque voluptatem.","price":98617.78,"header":"Placeat et cumque sit.","footer":"Architecto voluptatum et aut.","moreInfo":"Consequatur ullam voluptatibus accusantium."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
