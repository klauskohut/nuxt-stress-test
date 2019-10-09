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
      return {"slug":"fuga_ut","name":"Placeat ducimus deleniti est.","description":"Optio facilis praesentium. Voluptatibus ipsa id. Qui non libero.","price":86467.23,"header":"Vel voluptates hic distinctio.","footer":"Atque doloribus ipsam possimus.","moreInfo":"Ut corporis quibusdam est."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
