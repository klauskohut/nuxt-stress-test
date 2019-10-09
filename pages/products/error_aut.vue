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
      return {"slug":"error_aut","name":"Quo vel esse soluta.","description":"Est autem quia. Qui omnis sed. Est eveniet qui.","price":97339.93,"header":"Ipsum consequatur aut ullam.","footer":"Eos quibusdam sed sit.","moreInfo":"Velit est rerum quibusdam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
