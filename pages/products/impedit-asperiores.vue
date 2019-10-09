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
      return {"slug":"impedit-asperiores","name":"Blanditiis ea assumenda maxime.","description":"Cum inventore molestiae. Excepturi rerum est. Et eum sit.","price":68541.03,"header":"Consequuntur nihil consequatur et.","footer":"Incidunt sunt sint eos.","moreInfo":"Dolorum voluptates sunt iste."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
