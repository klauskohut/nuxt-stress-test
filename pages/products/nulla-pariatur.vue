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
      return {"slug":"nulla-pariatur","name":"Excepturi cumque et beatae.","description":"Veniam cupiditate ipsa. Excepturi voluptatem quos. Nulla laborum inventore.","price":90163.61,"header":"Officia delectus quia sapiente.","footer":"Voluptates odio iste distinctio.","moreInfo":"Consequatur mollitia officia facilis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
