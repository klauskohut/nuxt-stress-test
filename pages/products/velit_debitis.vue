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
      return {"slug":"velit_debitis","name":"Quis nemo voluptatem autem.","description":"Tenetur itaque fuga. Necessitatibus suscipit fugiat. Facilis id vel.","price":69877.45,"header":"Cumque et nostrum error.","footer":"Voluptatem commodi consectetur quia.","moreInfo":"Quis eum facere consequatur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
