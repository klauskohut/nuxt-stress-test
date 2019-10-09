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
      return {"slug":"consectetur_nemo","name":"Qui architecto officia sunt.","description":"Amet quia dolores. Rerum sint sint. Nesciunt fugit placeat.","price":51800.02,"header":"Veniam non labore aut.","footer":"Soluta officia voluptatibus minus.","moreInfo":"Qui consequatur dolores fugit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
