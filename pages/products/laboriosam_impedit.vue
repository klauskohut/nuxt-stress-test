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
      return {"slug":"laboriosam_impedit","name":"A qui maxime ut.","description":"A libero doloremque. Iure ratione voluptates. Voluptatum quo at.","price":62443.06,"header":"Sit voluptas rerum qui.","footer":"Ad placeat ea earum.","moreInfo":"Est quisquam exercitationem aspernatur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
