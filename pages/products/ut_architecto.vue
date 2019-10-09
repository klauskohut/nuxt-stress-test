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
      return {"slug":"ut_architecto","name":"Voluptas quaerat fugit provident.","description":"Ut fuga quas. Animi odio veniam. Ipsam omnis dolorum.","price":38750.97,"header":"Blanditiis porro et voluptate.","footer":"Sit est doloribus laborum.","moreInfo":"Numquam quisquam laborum est."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
