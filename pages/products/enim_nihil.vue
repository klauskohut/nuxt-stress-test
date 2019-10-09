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
      return {"slug":"enim_nihil","name":"Totam ratione dolores qui.","description":"Repudiandae autem praesentium. Exercitationem vel impedit. Dolorem quia facilis.","price":10526.18,"header":"Est facere nesciunt minima.","footer":"Exercitationem alias explicabo quos.","moreInfo":"Sit quibusdam eaque doloribus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
