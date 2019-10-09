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
      return {"slug":"voluptate-occaecati","name":"Consequatur quo nam quas.","description":"Ducimus sit laborum. Architecto temporibus eveniet. Placeat ea hic.","price":71650.36,"header":"Et enim autem culpa.","footer":"Autem laborum in praesentium.","moreInfo":"Nulla cumque sit est."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
