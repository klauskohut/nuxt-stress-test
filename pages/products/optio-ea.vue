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
      return {"slug":"optio-ea","name":"Expedita facilis atque recusandae.","description":"Unde qui ut. Et ut ex. Nihil neque perspiciatis.","price":64349.74,"header":"Vel quibusdam ipsam unde.","footer":"Et ratione aperiam deserunt.","moreInfo":"Eius animi omnis non."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
