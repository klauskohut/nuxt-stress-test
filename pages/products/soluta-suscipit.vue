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
      return {"slug":"soluta-suscipit","name":"Delectus nihil aut aspernatur.","description":"Quo quisquam nihil. Consequatur quis necessitatibus. Repellat qui facere.","price":37442.19,"header":"Sunt ipsum sunt voluptas.","footer":"Eum ut voluptates commodi.","moreInfo":"Quia dolor similique quod."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
