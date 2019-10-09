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
      return {"slug":"velit-omnis","name":"Non sint optio fugit.","description":"Et aut in. Omnis praesentium et. Praesentium voluptates nihil.","price":50880.31,"header":"Nesciunt id et ut.","footer":"Aspernatur eaque aperiam et.","moreInfo":"Corrupti earum adipisci est."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
