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
      return {"slug":"voluptatem-ea","name":"Neque magnam in in.","description":"Quia enim excepturi. Id porro ut. Expedita at quia.","price":33231.95,"header":"Molestiae nemo saepe unde.","footer":"Veniam et blanditiis provident.","moreInfo":"Qui neque consequuntur esse."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
