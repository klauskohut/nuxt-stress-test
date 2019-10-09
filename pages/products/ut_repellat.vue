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
      return {"slug":"ut_repellat","name":"Fugit reiciendis consequatur quia.","description":"Tempora dolorem odio. Omnis consequatur molestiae. Dolorum facilis voluptate.","price":15213.87,"header":"Id sit inventore porro.","footer":"Quia voluptatem quaerat ipsam.","moreInfo":"Et quae quidem pariatur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
