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
      return {"slug":"fuga-non","name":"Et quia maiores fugiat.","description":"Recusandae praesentium qui. Expedita occaecati modi. Occaecati fugit vero.","price":78137.95,"header":"Itaque voluptatem sit et.","footer":"Dolores ducimus repellat aspernatur.","moreInfo":"Nulla omnis repellendus nihil."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
