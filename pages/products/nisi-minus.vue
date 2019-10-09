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
      return {"slug":"nisi-minus","name":"Commodi ab ipsum similique.","description":"Et quam commodi. Dolor ipsum voluptas. Et omnis et.","price":20905.82,"header":"Perferendis neque reiciendis sequi.","footer":"Sed ab dolor est.","moreInfo":"Explicabo itaque eum pariatur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
