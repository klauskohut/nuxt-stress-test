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
      return {"slug":"blanditiis_sit","name":"Et amet aliquam harum.","description":"Aspernatur nam eveniet. Ratione ut nulla. Dolor deleniti quis.","price":31542.27,"header":"Consequatur voluptatem ex aut.","footer":"Fugiat autem perferendis eos.","moreInfo":"Beatae quis eligendi et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
