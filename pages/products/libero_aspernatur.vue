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
      return {"slug":"libero_aspernatur","name":"Enim totam omnis officiis.","description":"Adipisci ullam accusamus. Adipisci animi in. Unde tempore voluptatem.","price":89702.29,"header":"Delectus aut voluptatem ut.","footer":"Maxime quasi hic aliquam.","moreInfo":"Id unde et ex."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
