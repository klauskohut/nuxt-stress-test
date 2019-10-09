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
      return {"slug":"nihil-earum","name":"Non dolore sunt et.","description":"Dolor ea quas. Fugit praesentium in. Ea ad ea.","price":97349.54,"header":"Eveniet aut et atque.","footer":"Unde numquam atque aut.","moreInfo":"Et et voluptatem non."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
