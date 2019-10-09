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
      return {"slug":"dolore_ipsa","name":"Debitis corrupti vel consequatur.","description":"Nisi eligendi blanditiis. Aperiam fugiat animi. Quia sed et.","price":21463.37,"header":"Amet qui aut sint.","footer":"Aspernatur fugit autem animi.","moreInfo":"Tempora placeat labore perspiciatis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
