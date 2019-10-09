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
      return {"slug":"reprehenderit_ut","name":"Eos dolor eligendi et.","description":"Facere rerum fugit. Dicta aspernatur aut. Reiciendis aut eius.","price":90951.69,"header":"At omnis a deserunt.","footer":"Sint ut nulla incidunt.","moreInfo":"Enim qui et accusantium."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
