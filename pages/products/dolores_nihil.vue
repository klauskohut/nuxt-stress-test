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
      return {"slug":"dolores_nihil","name":"Maiores molestiae repellat molestiae.","description":"Eius sed at. Nisi eum est. Quisquam non aliquid.","price":79656.67,"header":"Harum iusto reiciendis pariatur.","footer":"Dolore ut harum totam.","moreInfo":"Nisi ducimus recusandae et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
