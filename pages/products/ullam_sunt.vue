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
      return {"slug":"ullam_sunt","name":"Doloremque unde quisquam facere.","description":"Temporibus omnis sunt. Aut non vel. Nulla ut veniam.","price":97912.47,"header":"Omnis tenetur qui non.","footer":"Quas quos porro est.","moreInfo":"Dolor voluptatem debitis esse."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
