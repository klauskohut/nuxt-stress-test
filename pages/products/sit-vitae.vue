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
      return {"slug":"sit-vitae","name":"Est itaque minima est.","description":"Ut nulla vitae. Nihil deleniti consequatur. Magni est minima.","price":30682.57,"header":"Unde mollitia temporibus sint.","footer":"Voluptas qui expedita fuga.","moreInfo":"Aliquam magni perferendis velit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
