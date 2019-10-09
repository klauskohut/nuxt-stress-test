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
      return {"slug":"sunt_quos","name":"Suscipit ab aut totam.","description":"Illum ut vitae. Pariatur voluptas est. Dolores sit id.","price":92849.96,"header":"Aut ut ea tenetur.","footer":"Voluptas consectetur quisquam molestiae.","moreInfo":"Est mollitia omnis minima."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
