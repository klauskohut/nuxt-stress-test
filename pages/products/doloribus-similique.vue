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
      return {"slug":"doloribus-similique","name":"Hic enim est suscipit.","description":"Sequi libero reprehenderit. Maiores aliquid cumque. Commodi voluptatem maxime.","price":62832.88,"header":"Omnis aliquid ex rerum.","footer":"Eum expedita ipsam ratione.","moreInfo":"Non dolore consequatur ea."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
