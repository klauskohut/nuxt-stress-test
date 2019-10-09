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
      return {"slug":"dolore-ut","name":"Perferendis nisi enim necessitatibus.","description":"Itaque velit enim. Totam libero blanditiis. Soluta quis itaque.","price":49780.44,"header":"Maxime omnis deserunt sit.","footer":"Corrupti distinctio saepe perferendis.","moreInfo":"Voluptatem qui porro temporibus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
