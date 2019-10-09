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
      return {"slug":"cumque-mollitia","name":"Omnis necessitatibus corrupti impedit.","description":"Laudantium ea similique. Laborum et ipsam. Nihil omnis esse.","price":11653.84,"header":"Aut ea placeat eum.","footer":"Aperiam reiciendis aut est.","moreInfo":"Aperiam totam necessitatibus dolorem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
