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
      return {"slug":"provident_quia","name":"Aut est laudantium voluptatem.","description":"Illo accusantium at. Optio inventore assumenda. Maiores deleniti cupiditate.","price":68117.12,"header":"At voluptas esse cumque.","footer":"Ut impedit facere molestias.","moreInfo":"Odit ullam earum modi."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
