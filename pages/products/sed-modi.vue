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
      return {"slug":"sed-modi","name":"Voluptatem impedit labore blanditiis.","description":"Id dicta tempore. Ipsam earum consequatur. Voluptate dignissimos enim.","price":88162.05,"header":"Sit possimus non magnam.","footer":"Tempora eum quam consequatur.","moreInfo":"Veniam perspiciatis debitis et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
