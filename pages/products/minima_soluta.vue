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
      return {"slug":"minima_soluta","name":"Necessitatibus fuga modi et.","description":"Quidem ipsum voluptates. Error magni sunt. Tempora quaerat nam.","price":74030.92,"header":"Aperiam expedita saepe sunt.","footer":"Non non aut consequatur.","moreInfo":"Sit pariatur officiis provident."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
