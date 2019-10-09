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
      return {"slug":"voluptatem_fugit","name":"Expedita voluptatem quam sit.","description":"Dignissimos ut recusandae. Sit delectus doloremque. Voluptatem adipisci non.","price":97929.42,"header":"Accusantium officia tempore et.","footer":"Autem eaque qui dolor.","moreInfo":"Necessitatibus sit molestiae totam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
