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
      return {"slug":"cumque-non","name":"Accusantium accusamus ut itaque.","description":"Incidunt id laboriosam. Quas ipsum optio. Laborum ut vel.","price":30401.62,"header":"Odit eum voluptates autem.","footer":"Ea iure accusamus beatae.","moreInfo":"Voluptatem eaque sed totam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
