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
      return {"slug":"minus_aut","name":"In maiores voluptas aut.","description":"Assumenda minima qui. Vitae accusantium quis. Rerum dolores impedit.","price":37903.32,"header":"Enim pariatur temporibus exercitationem.","footer":"Similique sint pariatur sunt.","moreInfo":"Quidem perferendis temporibus et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
