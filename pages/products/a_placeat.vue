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
      return {"slug":"a_placeat","name":"Consequatur eos provident voluptates.","description":"Quam beatae ipsam. Cumque sapiente ut. Itaque molestias qui.","price":13381.87,"header":"Unde sapiente omnis est.","footer":"Quibusdam fugit ad sunt.","moreInfo":"Dolor quos sint accusantium."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
