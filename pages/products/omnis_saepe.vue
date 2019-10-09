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
      return {"slug":"omnis_saepe","name":"Dolor eveniet voluptate culpa.","description":"Fugiat vero est. Perspiciatis architecto dolores. Qui voluptate ullam.","price":79098.02,"header":"Voluptate consequatur ut vel.","footer":"Beatae ipsa aut nihil.","moreInfo":"Nostrum velit error voluptatem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
