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
      return {"slug":"architecto-doloremque","name":"Deleniti corporis quisquam temporibus.","description":"Quam esse id. Quibusdam laudantium sed. Nulla alias qui.","price":43862.65,"header":"Et quis minima assumenda.","footer":"Sint eaque rerum optio.","moreInfo":"Perferendis ratione porro et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
