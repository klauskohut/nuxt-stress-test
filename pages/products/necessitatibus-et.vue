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
      return {"slug":"necessitatibus-et","name":"Alias accusamus id laudantium.","description":"At est minus. Dolor ipsum recusandae. Omnis assumenda vitae.","price":37544.52,"header":"Quos qui iure voluptatibus.","footer":"Repellendus architecto dicta ut.","moreInfo":"Quia aut dolor repellendus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
