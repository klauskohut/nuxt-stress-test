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
      return {"slug":"beatae_molestiae","name":"Temporibus ea velit rem.","description":"Reiciendis voluptates facere. Facere sit expedita. Inventore sequi iste.","price":83672.77,"header":"Facilis voluptate alias ullam.","footer":"Sunt quis autem illum.","moreInfo":"Rerum ipsum debitis voluptate."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
