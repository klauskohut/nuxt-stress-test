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
      return {"slug":"enim_dolores","name":"Quisquam atque id quo.","description":"Et ut facilis. Dolorem suscipit quia. Consequatur suscipit aspernatur.","price":60960.79,"header":"Qui maxime officia velit.","footer":"Id ab qui voluptatem.","moreInfo":"Nihil aspernatur veritatis et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
