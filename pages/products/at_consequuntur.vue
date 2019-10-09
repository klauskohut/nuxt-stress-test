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
      return {"slug":"at_consequuntur","name":"Earum eius mollitia et.","description":"Accusamus sed praesentium. Qui recusandae quaerat. Tenetur aut perferendis.","price":14590.87,"header":"Odit consequuntur esse voluptatem.","footer":"Sed soluta quas expedita.","moreInfo":"Vel voluptatem molestiae eos."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
