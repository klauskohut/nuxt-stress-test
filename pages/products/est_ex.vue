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
      return {"slug":"est_ex","name":"Tempore facilis ab beatae.","description":"Rerum consectetur doloribus. Aut soluta similique. Optio possimus quisquam.","price":13713.82,"header":"Sint ut ducimus beatae.","footer":"Qui eos rem voluptates.","moreInfo":"Natus est molestiae sint."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
