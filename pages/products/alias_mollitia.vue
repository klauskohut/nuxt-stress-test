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
      return {"slug":"alias_mollitia","name":"Voluptates beatae pariatur aspernatur.","description":"Ut adipisci exercitationem. Ipsam officia quam. Perspiciatis sit quaerat.","price":85421.48,"header":"Error debitis adipisci in.","footer":"Vel qui excepturi ut.","moreInfo":"Voluptatum vel voluptas accusamus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
