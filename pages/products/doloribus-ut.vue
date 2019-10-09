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
      return {"slug":"doloribus-ut","name":"Repudiandae vel facilis itaque.","description":"Veniam non aspernatur. Iure minima itaque. Voluptas eius aut.","price":56903.26,"header":"Sint ea ullam et.","footer":"Excepturi et ratione voluptatem.","moreInfo":"Sit minus accusamus odit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
