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
      return {"slug":"nulla-aut","name":"Quam et et earum.","description":"Nihil qui quis. Possimus laborum distinctio. Et provident autem.","price":97114.62,"header":"Commodi accusantium et aliquid.","footer":"Harum error odit quis.","moreInfo":"Id voluptatem consequatur rerum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
