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
      return {"slug":"eveniet_odio","name":"Est labore qui harum.","description":"Quae sit ab. Ratione pariatur et. Et pariatur magnam.","price":85869.86,"header":"Perspiciatis sed corporis ut.","footer":"In aut et et.","moreInfo":"Et sapiente corporis fugiat."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
