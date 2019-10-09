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
      return {"slug":"nulla_voluptate","name":"Iusto maxime consequuntur tenetur.","description":"Veritatis quibusdam deserunt. Iste deleniti minima. Sit sint vel.","price":81679.13,"header":"Sed harum iusto eius.","footer":"Nihil provident sequi rerum.","moreInfo":"Consectetur eveniet tempora suscipit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
