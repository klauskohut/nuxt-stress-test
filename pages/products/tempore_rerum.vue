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
      return {"slug":"tempore_rerum","name":"Dolor porro necessitatibus explicabo.","description":"Sed maxime quis. Autem explicabo esse. Et atque facilis.","price":70760.94,"header":"Quis neque ut et.","footer":"Est unde aut ut.","moreInfo":"Nulla rerum est odio."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
