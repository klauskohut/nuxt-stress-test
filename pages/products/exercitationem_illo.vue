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
      return {"slug":"exercitationem_illo","name":"Vitae laboriosam eveniet nulla.","description":"Ut sequi optio. Quam nostrum aspernatur. Ipsum aut beatae.","price":86476.28,"header":"Quae nam voluptatem aut.","footer":"Ullam quos nulla quo.","moreInfo":"Ea aut quisquam consequatur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
