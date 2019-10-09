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
      return {"slug":"labore-minus","name":"Qui voluptatem maiores deleniti.","description":"Delectus aut vitae. Ullam porro nesciunt. Sed voluptates explicabo.","price":50503.55,"header":"Qui odio et consequatur.","footer":"Quisquam laboriosam esse quam.","moreInfo":"Aut repellendus recusandae cum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
