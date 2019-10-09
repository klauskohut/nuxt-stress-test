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
      return {"slug":"eum_doloribus","name":"Tempore voluptatem voluptate vel.","description":"Blanditiis est non. Dolorum quasi sit. Commodi ut doloribus.","price":67829.61,"header":"Id consectetur est autem.","footer":"Ipsam illo vel autem.","moreInfo":"Enim facilis non saepe."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
