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
      return {"slug":"ab_quidem","name":"Ipsa incidunt labore cum.","description":"Impedit a accusantium. Est atque velit. Sapiente illo et.","price":45366.65,"header":"Non saepe est itaque.","footer":"Qui voluptatem et omnis.","moreInfo":"Illum nostrum aut illo."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
