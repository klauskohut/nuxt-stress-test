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
      return {"slug":"qui-autem","name":"Ut quidem neque est.","description":"Est dolores quia. Est voluptates illo. Eius ut quae.","price":28086.17,"header":"Non nulla minus voluptates.","footer":"Sed in sint aliquam.","moreInfo":"Blanditiis fugit vitae aliquid."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
