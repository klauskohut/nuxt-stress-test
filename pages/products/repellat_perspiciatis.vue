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
      return {"slug":"repellat_perspiciatis","name":"Vitae aliquam atque aut.","description":"Ea omnis earum. Harum quibusdam nulla. Debitis excepturi commodi.","price":71247.36,"header":"Inventore quaerat sed aspernatur.","footer":"Id voluptatem sed aut.","moreInfo":"Id ut ab quas."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
