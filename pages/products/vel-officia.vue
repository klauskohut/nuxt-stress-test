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
      return {"slug":"vel-officia","name":"Unde praesentium ipsam velit.","description":"Laboriosam esse earum. Ea ullam culpa. Voluptates sed doloribus.","price":58229.03,"header":"Et nihil perferendis quisquam.","footer":"Unde et culpa adipisci.","moreInfo":"Non veniam suscipit ea."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
