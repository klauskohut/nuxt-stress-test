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
      return {"slug":"voluptates_qui","name":"Sunt officiis porro qui.","description":"Aliquam dolores nisi. Quas error aliquam. Asperiores quaerat ut.","price":33800.53,"header":"In cumque sapiente eos.","footer":"Aliquid enim voluptatem quasi.","moreInfo":"Est sint eaque officiis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
