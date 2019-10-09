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
      return {"slug":"sed_amet","name":"Voluptatem laborum est reprehenderit.","description":"Nam eaque temporibus. Non fugit eos. Et occaecati aspernatur.","price":18740.69,"header":"Aperiam sit molestiae debitis.","footer":"Consequatur quia nam unde.","moreInfo":"Et provident numquam itaque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
