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
      return {"slug":"et-et","name":"Laborum est quis et.","description":"Aliquid aperiam recusandae. Ea a dicta. Sed ullam dolores.","price":84141.84,"header":"Eligendi numquam possimus suscipit.","footer":"Hic sunt est quia.","moreInfo":"Quis atque non sunt."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
