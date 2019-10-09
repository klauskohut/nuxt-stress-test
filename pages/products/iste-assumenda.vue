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
      return {"slug":"iste-assumenda","name":"Fuga velit consequatur quia.","description":"Consequatur aut quis. Soluta qui vero. Distinctio labore praesentium.","price":39295.73,"header":"Qui asperiores quis enim.","footer":"Nostrum sit est dolor.","moreInfo":"Nesciunt dolorem mollitia dolor."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
