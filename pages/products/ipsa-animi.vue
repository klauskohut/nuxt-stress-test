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
      return {"slug":"ipsa-animi","name":"Facilis dignissimos nam ut.","description":"Sit aspernatur cupiditate. Accusamus illum aut. Qui alias eligendi.","price":99861.95,"header":"Mollitia et recusandae saepe.","footer":"Sed aut et magni.","moreInfo":"Ratione dolorem ut expedita."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
