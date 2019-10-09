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
      return {"slug":"nam_vel","name":"Est id aut sunt.","description":"Reprehenderit aspernatur provident. Veritatis maxime facere. Facere in quis.","price":15396.31,"header":"Voluptate ducimus molestiae et.","footer":"Eius omnis velit sapiente.","moreInfo":"Vero ut quo ut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
