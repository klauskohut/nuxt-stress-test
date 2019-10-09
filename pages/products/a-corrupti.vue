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
      return {"slug":"a-corrupti","name":"Eum beatae voluptatibus sequi.","description":"Mollitia consectetur assumenda. Aliquid doloribus aut. Explicabo quia et.","price":15409.73,"header":"Iure itaque id consectetur.","footer":"Maiores perspiciatis quae odio.","moreInfo":"Officia a amet corporis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
