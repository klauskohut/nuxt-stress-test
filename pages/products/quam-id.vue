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
      return {"slug":"quam-id","name":"Aliquid suscipit ut qui.","description":"Hic doloribus provident. Quidem pariatur iste. Omnis sed veritatis.","price":33988.79,"header":"Aliquam impedit inventore et.","footer":"Iste quod ex eum.","moreInfo":"Quos mollitia maiores dolores."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
