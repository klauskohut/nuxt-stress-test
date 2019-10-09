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
      return {"slug":"natus-eaque","name":"Accusantium sint impedit qui.","description":"Magnam et vitae. Similique dignissimos labore. Assumenda aut modi.","price":32982.08,"header":"Dolor deserunt numquam voluptate.","footer":"Saepe rem quibusdam harum.","moreInfo":"Accusantium eum sunt voluptates."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
