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
      return {"slug":"eum_eum","name":"In corporis debitis qui.","description":"Voluptatem expedita rerum. Voluptas odit laudantium. Ipsum quos nemo.","price":59081.17,"header":"Omnis ipsam et iure.","footer":"Aliquam quos velit et.","moreInfo":"Aliquid dolorem vel ex."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
