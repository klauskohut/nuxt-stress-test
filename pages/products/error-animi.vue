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
      return {"slug":"error-animi","name":"Eos hic doloribus accusamus.","description":"Vel id voluptatem. Quo adipisci quasi. Non et consequuntur.","price":30470.37,"header":"Nesciunt commodi harum tenetur.","footer":"Animi ratione nihil temporibus.","moreInfo":"Rerum pariatur et adipisci."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
