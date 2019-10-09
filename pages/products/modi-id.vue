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
      return {"slug":"modi-id","name":"Et eos rerum corrupti.","description":"Iste et harum. Dolorum dolor laboriosam. Illum vel vero.","price":82729.44,"header":"Corrupti dolores accusantium nostrum.","footer":"In aliquid id nam.","moreInfo":"Ab cupiditate consequatur incidunt."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
