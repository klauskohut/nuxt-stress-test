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
      return {"slug":"eum-harum","name":"Voluptatibus optio minus rerum.","description":"Fugit doloremque provident. Aut repellendus laudantium. Consequatur molestiae est.","price":68429.81,"header":"Magnam qui et debitis.","footer":"Corrupti sint consequatur eligendi.","moreInfo":"Quasi suscipit omnis est."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
