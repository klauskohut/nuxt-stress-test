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
      return {"slug":"nisi-in","name":"Praesentium vitae temporibus eligendi.","description":"Suscipit quia porro. Esse molestiae facere. Molestiae expedita alias.","price":81598.12,"header":"Rerum amet voluptate soluta.","footer":"Dolorem eaque officiis sit.","moreInfo":"Totam quam atque facere."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
