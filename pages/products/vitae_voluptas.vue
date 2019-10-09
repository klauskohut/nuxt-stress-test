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
      return {"slug":"vitae_voluptas","name":"Ea sit at sint.","description":"Molestiae tempora dolore. Quae ducimus velit. Nostrum sed dolores.","price":93539.23,"header":"Reiciendis dolorem cum illum.","footer":"Quo aut molestiae voluptas.","moreInfo":"Quaerat qui aut consequatur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
