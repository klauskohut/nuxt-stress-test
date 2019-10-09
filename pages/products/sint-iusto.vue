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
      return {"slug":"sint-iusto","name":"Nihil aut repellendus sint.","description":"Maiores repellat vero. Voluptate consequatur sint. Placeat aut velit.","price":66360.96,"header":"Aliquid dolores ipsa aspernatur.","footer":"Aliquid dicta eum quia.","moreInfo":"Nisi rerum quisquam fugiat."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
