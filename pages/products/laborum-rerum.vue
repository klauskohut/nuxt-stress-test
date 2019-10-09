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
      return {"slug":"laborum-rerum","name":"Inventore voluptas quis provident.","description":"Ipsa iusto deserunt. Qui sapiente odio. Totam architecto odio.","price":66838.79,"header":"Id ut et officiis.","footer":"Autem qui minus possimus.","moreInfo":"Placeat ut sint expedita."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
