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
      return {"slug":"occaecati-pariatur","name":"Dolorem ratione maxime amet.","description":"Dolores minima aut. Et ut dignissimos. Aperiam qui est.","price":54218.75,"header":"Facere ut cumque cum.","footer":"Rerum aut et commodi.","moreInfo":"Rerum consectetur beatae amet."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
