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
      return {"slug":"quibusdam-sit","name":"Ab incidunt sunt ut.","description":"Et ipsa ut. Suscipit quo non. Quam necessitatibus illum.","price":26785.74,"header":"Et nisi ut et.","footer":"Error ad quaerat pariatur.","moreInfo":"Molestiae quisquam qui modi."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
