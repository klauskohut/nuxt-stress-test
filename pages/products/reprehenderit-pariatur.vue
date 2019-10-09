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
      return {"slug":"reprehenderit-pariatur","name":"Facere hic odio explicabo.","description":"Delectus fuga consequatur. Ab nobis eaque. Culpa et quae.","price":80683.32,"header":"Id suscipit ad voluptatum.","footer":"Eaque cumque eum eos.","moreInfo":"Rerum minus distinctio modi."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
