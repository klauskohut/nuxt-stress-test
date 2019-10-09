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
      return {"slug":"animi-quae","name":"Dolorum perferendis voluptas voluptate.","description":"Aut consequatur labore. Impedit consequuntur optio. Blanditiis dolores quam.","price":68656.22,"header":"Possimus nemo ut eligendi.","footer":"Provident molestias eaque in.","moreInfo":"Omnis ut expedita officiis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
