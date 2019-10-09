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
      return {"slug":"accusantium_sequi","name":"Qui esse quo quia.","description":"Quidem sed reprehenderit. Animi nihil aut. Neque maiores consequatur.","price":66923.59,"header":"Modi similique dignissimos recusandae.","footer":"Mollitia iusto consequatur omnis.","moreInfo":"Et sunt sit iusto."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
