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
      return {"slug":"quasi-iure","name":"Nostrum ipsa distinctio nobis.","description":"Ex recusandae et. Quis excepturi libero. Voluptate est culpa.","price":65027.64,"header":"Deserunt distinctio sit voluptatem.","footer":"Ut quia dolores consequatur.","moreInfo":"Et iusto velit inventore."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
