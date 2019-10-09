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
      return {"slug":"laboriosam_corporis","name":"Omnis ullam et aspernatur.","description":"Quia earum aut. Omnis ipsum quia. Aliquid dolore qui.","price":74926.32,"header":"Sunt explicabo nam saepe.","footer":"Laboriosam excepturi aut nesciunt.","moreInfo":"Consequatur impedit at est."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
