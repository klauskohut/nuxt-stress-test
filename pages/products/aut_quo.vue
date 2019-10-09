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
      return {"slug":"aut_quo","name":"Sequi sed non commodi.","description":"Deleniti illum omnis. Incidunt cumque iusto. Libero id est.","price":59717.58,"header":"Quis atque deserunt minima.","footer":"Sapiente non vel et.","moreInfo":"Magnam maiores est ducimus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
