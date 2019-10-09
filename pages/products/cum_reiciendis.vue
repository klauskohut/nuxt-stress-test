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
      return {"slug":"cum_reiciendis","name":"Voluptates et non voluptatibus.","description":"Quo nihil vel. Quae id voluptatem. Voluptate voluptas dicta.","price":21840.96,"header":"Et cum voluptas dolore.","footer":"Autem saepe nobis magni.","moreInfo":"Tempora odit consequatur expedita."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
