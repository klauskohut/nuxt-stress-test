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
      return {"slug":"qui_et","name":"Ad consequatur error consequatur.","description":"Repudiandae voluptatem et. Sed recusandae ipsum. Velit officia voluptatem.","price":14384.31,"header":"Ut consequuntur dicta dignissimos.","footer":"Velit cum libero minus.","moreInfo":"Sit similique magnam veniam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
