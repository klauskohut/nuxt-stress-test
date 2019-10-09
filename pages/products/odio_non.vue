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
      return {"slug":"odio_non","name":"Cum sunt doloribus maxime.","description":"Illum quidem ipsam. Voluptatem doloribus adipisci. Repellat quos soluta.","price":74588.62,"header":"Laborum praesentium qui sapiente.","footer":"Id corrupti fugiat non.","moreInfo":"Voluptas perspiciatis officia possimus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
