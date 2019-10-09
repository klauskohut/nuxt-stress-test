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
      return {"slug":"nulla-aliquid","name":"Debitis nobis officiis error.","description":"Eum iure rerum. Ut exercitationem qui. Eligendi eveniet eius.","price":27601.76,"header":"Delectus rem eum et.","footer":"Porro necessitatibus explicabo et.","moreInfo":"Sunt vitae eius sit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
