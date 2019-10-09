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
      return {"slug":"doloribus-in","name":"Tenetur et aut numquam.","description":"Aut vero voluptates. Sit eos quos. Magni ipsam velit.","price":56862.86,"header":"Minima repudiandae accusantium voluptatem.","footer":"Tempora nostrum ut et.","moreInfo":"Vel consequatur unde quia."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
