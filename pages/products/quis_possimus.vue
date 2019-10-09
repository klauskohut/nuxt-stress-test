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
      return {"slug":"quis_possimus","name":"Accusamus nesciunt qui dignissimos.","description":"Velit repudiandae et. Quidem illum quos. Necessitatibus nulla nihil.","price":92711.42,"header":"Est rerum quia fugit.","footer":"Enim voluptas dolor recusandae.","moreInfo":"Laudantium in et inventore."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
