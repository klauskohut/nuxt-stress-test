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
      return {"slug":"non_sunt","name":"Fugiat maxime vitae ipsum.","description":"Placeat aut et. Nesciunt ut a. Quo omnis molestiae.","price":80129.98,"header":"Quis voluptatum suscipit voluptas.","footer":"Consequatur deserunt natus eveniet.","moreInfo":"Id corporis vel aliquam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
