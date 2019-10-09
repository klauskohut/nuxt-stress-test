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
      return {"slug":"sit-tempore","name":"Praesentium corporis fugit nemo.","description":"Voluptate sint aut. Ea accusamus beatae. A odit amet.","price":99064.64,"header":"Et voluptas perspiciatis optio.","footer":"Quo suscipit quas minus.","moreInfo":"Autem vel sequi ipsum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
