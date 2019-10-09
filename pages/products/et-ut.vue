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
      return {"slug":"et-ut","name":"Quidem eius nihil consequuntur.","description":"Hic libero ullam. Fugit optio est. Est corporis aspernatur.","price":58208.77,"header":"Nihil fuga error sunt.","footer":"Illum quibusdam dolorem laudantium.","moreInfo":"Ut porro iure id."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
