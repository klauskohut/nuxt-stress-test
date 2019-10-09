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
      return {"slug":"omnis_blanditiis","name":"Aut deleniti eum nostrum.","description":"Eos qui et. Aut saepe quis. Aliquam possimus labore.","price":86237.31,"header":"Qui velit ipsam impedit.","footer":"Voluptas aut ullam dolorem.","moreInfo":"Eius doloremque tempora eos."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
