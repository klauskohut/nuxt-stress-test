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
      return {"slug":"ab-voluptas","name":"Quae minima unde ad.","description":"Quod ipsa commodi. Voluptatem placeat omnis. Ea aut dignissimos.","price":75145.25,"header":"Est optio voluptates deleniti.","footer":"Est pariatur consequuntur aut.","moreInfo":"Dolorem facilis repellendus qui."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
