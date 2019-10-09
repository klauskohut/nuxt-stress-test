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
      return {"slug":"inventore-officia","name":"Quisquam aut recusandae aut.","description":"Iure similique quaerat. Corporis voluptatem quidem. Ullam quis aut.","price":45415.68,"header":"Exercitationem dolores sed est.","footer":"Et ducimus adipisci non.","moreInfo":"Aut quae id in."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
