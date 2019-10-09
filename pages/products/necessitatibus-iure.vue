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
      return {"slug":"necessitatibus-iure","name":"Ea sapiente sit quia.","description":"Maiores et laborum. Ea saepe a. Tempore magni laudantium.","price":63122.12,"header":"In magni aspernatur et.","footer":"Expedita sit aut sequi.","moreInfo":"Et unde occaecati quisquam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
