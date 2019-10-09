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
      return {"slug":"debitis_pariatur","name":"Qui esse eum accusantium.","description":"Eos commodi laborum. Rerum placeat veniam. Ipsam culpa ducimus.","price":26109.65,"header":"Accusantium quam expedita corporis.","footer":"Earum expedita omnis porro.","moreInfo":"Vitae aut cum ut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
