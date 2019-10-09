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
      return {"slug":"sit_enim","name":"Fuga placeat saepe voluptate.","description":"Atque rerum reprehenderit. Soluta rerum aliquid. Libero aspernatur sint.","price":13907.83,"header":"Est quos est consequatur.","footer":"Corrupti et iusto autem.","moreInfo":"Aut fuga commodi animi."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
