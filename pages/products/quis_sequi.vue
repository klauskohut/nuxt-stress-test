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
      return {"slug":"quis_sequi","name":"Quaerat quidem distinctio quia.","description":"Consequuntur nemo illum. Labore inventore consectetur. Commodi ut ab.","price":11481.29,"header":"Aut ullam iste est.","footer":"Vitae rem non debitis.","moreInfo":"Ducimus est recusandae libero."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
