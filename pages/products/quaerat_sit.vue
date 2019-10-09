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
      return {"slug":"quaerat_sit","name":"Accusamus fugit quos et.","description":"Perferendis labore rerum. Et et minima. Neque modi sint.","price":98715.77,"header":"Doloremque sed modi nulla.","footer":"Vero mollitia quia voluptatem.","moreInfo":"Ea aliquid autem vel."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
