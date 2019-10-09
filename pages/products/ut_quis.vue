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
      return {"slug":"ut_quis","name":"Temporibus laborum animi enim.","description":"Provident qui voluptatibus. Unde sint ipsam. Praesentium odit itaque.","price":33516.88,"header":"Dolor veniam nihil aspernatur.","footer":"Labore possimus quidem quis.","moreInfo":"Et quam et perferendis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
