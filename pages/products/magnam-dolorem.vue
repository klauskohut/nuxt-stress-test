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
      return {"slug":"magnam-dolorem","name":"Sit fugiat deleniti culpa.","description":"Quis rerum sint. Ad reiciendis aliquid. Adipisci ut officia.","price":33435.99,"header":"Cumque qui odio dolorem.","footer":"Voluptatibus quidem ex consequatur.","moreInfo":"Culpa et molestiae velit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
