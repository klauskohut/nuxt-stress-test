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
      return {"slug":"laborum-iusto","name":"Unde eos nihil in.","description":"Adipisci eveniet qui. Rem quia omnis. Quas et enim.","price":95641.57,"header":"Quibusdam aut alias consequatur.","footer":"Consectetur nobis magnam quod.","moreInfo":"Et deserunt inventore veniam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
