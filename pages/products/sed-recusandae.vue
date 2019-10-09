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
      return {"slug":"sed-recusandae","name":"Quibusdam laborum eveniet iusto.","description":"Quasi est nulla. Non blanditiis velit. Veniam odit quis.","price":76357.18,"header":"Ut rerum deleniti iure.","footer":"Quas aut eum iusto.","moreInfo":"Provident architecto voluptatem omnis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
