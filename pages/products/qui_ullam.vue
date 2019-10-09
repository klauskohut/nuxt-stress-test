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
      return {"slug":"qui_ullam","name":"Sunt sed temporibus vero.","description":"Aut omnis adipisci. Aliquam dolorum deserunt. Harum error perspiciatis.","price":48225.23,"header":"Beatae veritatis soluta consequatur.","footer":"Illo molestiae quas dolores.","moreInfo":"Voluptatibus facere illum et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
