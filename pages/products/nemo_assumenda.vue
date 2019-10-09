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
      return {"slug":"nemo_assumenda","name":"Odit quia et pariatur.","description":"Rerum amet dolorem. Omnis non accusantium. Rerum quo quas.","price":71767.94,"header":"Rerum eaque recusandae consequatur.","footer":"Molestiae odio est qui.","moreInfo":"Dolores ipsam qui voluptas."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
