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
      return {"slug":"est_molestiae","name":"Fugit ea non sit.","description":"Corporis aut cum. Minima accusamus incidunt. Est sed magni.","price":66447.63,"header":"Maxime natus iure dolorum.","footer":"Iste maxime dolore consequatur.","moreInfo":"Corporis possimus fugit officiis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
