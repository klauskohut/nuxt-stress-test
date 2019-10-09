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
      return {"slug":"voluptates-ullam","name":"Quaerat sequi consequuntur voluptatem.","description":"Deleniti consectetur a. Et eligendi at. Maiores corrupti officia.","price":94168.65,"header":"Et ratione rem aperiam.","footer":"Est sint illo vero.","moreInfo":"Omnis et omnis est."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
