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
      return {"slug":"tempora-suscipit","name":"Nisi aut perspiciatis occaecati.","description":"Facilis repellat distinctio. Nesciunt est doloribus. Rerum sequi repudiandae.","price":12948.19,"header":"Aut quidem hic molestiae.","footer":"Quidem amet tempora aliquid.","moreInfo":"Quia ut quo eaque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
