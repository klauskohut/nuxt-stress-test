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
      return {"slug":"animi_dolores","name":"Non repudiandae nihil a.","description":"Quasi non doloribus. Nihil ea recusandae. Molestiae saepe voluptatem.","price":61486.27,"header":"Cum veniam ut dicta.","footer":"Excepturi quibusdam voluptate explicabo.","moreInfo":"Nobis ullam eaque odio."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
