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
      return {"slug":"sit_ut","name":"Sapiente corporis inventore vel.","description":"Qui rerum cumque. Consequatur quaerat voluptatem. Et optio voluptas.","price":73627.67,"header":"Sequi distinctio tempora fugit.","footer":"Et porro error reprehenderit.","moreInfo":"Voluptatem et dolores sed."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
