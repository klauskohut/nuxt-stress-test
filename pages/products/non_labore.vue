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
      return {"slug":"non_labore","name":"Laboriosam vel quia est.","description":"Et molestias praesentium. Debitis error ullam. Laudantium non nisi.","price":81856.92,"header":"Molestias nisi ut eos.","footer":"Et rerum rerum ipsam.","moreInfo":"Sed reprehenderit delectus rerum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
