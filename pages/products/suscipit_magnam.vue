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
      return {"slug":"suscipit_magnam","name":"Quaerat repellendus et voluptatem.","description":"Sed repellat eos. In minima ducimus. Qui ipsum mollitia.","price":82253.17,"header":"Modi quam corporis voluptatem.","footer":"Iste sit libero accusamus.","moreInfo":"Sed qui hic qui."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
