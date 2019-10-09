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
      return {"slug":"soluta_quia","name":"Voluptate eum ratione eos.","description":"Repellat maxime nihil. Magni neque a. Dolorem sed enim.","price":24141.53,"header":"Quos repudiandae libero nulla.","footer":"Accusantium aut velit numquam.","moreInfo":"Quo saepe est recusandae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
