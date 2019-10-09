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
      return {"slug":"molestiae-et","name":"Aliquam voluptas id nulla.","description":"Eum dolor ut. Quia molestias dolores. Quas vel aliquid.","price":53739.84,"header":"Explicabo nostrum expedita aspernatur.","footer":"Iure qui corrupti nulla.","moreInfo":"Necessitatibus aut iure a."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
