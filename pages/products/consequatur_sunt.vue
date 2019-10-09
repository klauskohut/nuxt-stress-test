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
      return {"slug":"consequatur_sunt","name":"Necessitatibus dolor tempore distinctio.","description":"Saepe rerum delectus. Est tenetur voluptate. Aut architecto assumenda.","price":18988.14,"header":"Dolorem repudiandae illum necessitatibus.","footer":"Temporibus blanditiis qui non.","moreInfo":"Repudiandae illum placeat vitae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
