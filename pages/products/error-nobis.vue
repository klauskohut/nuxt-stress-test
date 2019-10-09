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
      return {"slug":"error-nobis","name":"Placeat est deserunt fugit.","description":"Quidem harum consequatur. Aut vero qui. Amet nesciunt necessitatibus.","price":25077.63,"header":"Consequatur totam eum similique.","footer":"Quia atque nesciunt iste.","moreInfo":"Maiores dolores ex quisquam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
