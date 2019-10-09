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
      return {"slug":"sit_reprehenderit","name":"Tempora vel quia sit.","description":"Modi rerum velit. Dolorum magni ut. Nisi est optio.","price":91139.52,"header":"Odit blanditiis eos alias.","footer":"Ducimus expedita et id.","moreInfo":"Consequatur ipsa sint sed."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
