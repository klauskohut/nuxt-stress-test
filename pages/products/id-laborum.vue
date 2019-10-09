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
      return {"slug":"id-laborum","name":"Quod voluptas aspernatur consequatur.","description":"Voluptatem iste quis. Rerum perferendis non. Et omnis ullam.","price":22035.29,"header":"Impedit ea consequatur accusamus.","footer":"Excepturi repellat assumenda ut.","moreInfo":"Eligendi magni ut beatae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
