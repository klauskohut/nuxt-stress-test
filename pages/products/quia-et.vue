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
      return {"slug":"quia-et","name":"Culpa placeat earum similique.","description":"Reiciendis qui esse. Ut est ducimus. Quos nemo dolor.","price":63276.76,"header":"Placeat magnam similique nam.","footer":"Suscipit aspernatur doloremque dolorem.","moreInfo":"Incidunt perferendis velit quam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
