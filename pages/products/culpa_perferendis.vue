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
      return {"slug":"culpa_perferendis","name":"Aliquam blanditiis non nihil.","description":"Voluptas et et. Magnam veniam aspernatur. Modi ut aspernatur.","price":91189.39,"header":"Dolorem laborum eum optio.","footer":"Et blanditiis architecto illo.","moreInfo":"Eum tempore et placeat."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
