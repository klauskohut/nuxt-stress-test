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
      return {"slug":"incidunt-tempora","name":"Quidem ut commodi deleniti.","description":"Saepe doloremque quia. Ut modi in. Id adipisci ullam.","price":98824.36,"header":"Suscipit consequuntur et pariatur.","footer":"Iure corporis earum nobis.","moreInfo":"Quod nobis minus incidunt."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
