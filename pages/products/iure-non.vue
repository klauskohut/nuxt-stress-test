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
      return {"slug":"iure-non","name":"Numquam sint earum est.","description":"Deleniti ab fuga. Veniam ipsum et. Nam commodi dolorum.","price":52290.06,"header":"Facilis illum et praesentium.","footer":"Ut ipsum quidem corrupti.","moreInfo":"Et nam vero quos."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
