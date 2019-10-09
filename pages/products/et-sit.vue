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
      return {"slug":"et-sit","name":"Fugiat vitae laborum placeat.","description":"Nihil quibusdam molestias. Eius blanditiis non. Quaerat aspernatur ex.","price":71363.97,"header":"Laborum excepturi et error.","footer":"Vel facere nobis molestiae.","moreInfo":"Quisquam ab fugit quis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
