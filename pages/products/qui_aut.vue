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
      return {"slug":"qui_aut","name":"Voluptatem placeat vel eligendi.","description":"Temporibus optio eos. Quia magni non. Sint saepe ut.","price":29643.76,"header":"Quo vitae quaerat odio.","footer":"Ipsum perspiciatis velit eligendi.","moreInfo":"Quia porro incidunt eos."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
