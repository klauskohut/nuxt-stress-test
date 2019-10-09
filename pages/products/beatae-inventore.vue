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
      return {"slug":"beatae-inventore","name":"Nulla asperiores officia ullam.","description":"Hic aut cupiditate. Est dolores quasi. Tenetur unde vitae.","price":17812.85,"header":"At in qui temporibus.","footer":"Qui minima qui blanditiis.","moreInfo":"Fuga consequatur recusandae quis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
