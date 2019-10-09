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
      return {"slug":"ducimus_debitis","name":"In corporis quidem enim.","description":"Laborum porro quia. Cumque aut dolorum. Quaerat quam consequatur.","price":30694.75,"header":"Qui est illum suscipit.","footer":"Dolorem ea non vero.","moreInfo":"Et laudantium veritatis dolor."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
