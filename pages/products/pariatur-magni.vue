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
      return {"slug":"pariatur-magni","name":"Aperiam eos hic necessitatibus.","description":"Eaque aut quis. Ab ut quae. Dolores aliquid maiores.","price":87048.71,"header":"Nulla voluptatum alias inventore.","footer":"Omnis aut numquam sit.","moreInfo":"Ut rerum rerum ad."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
