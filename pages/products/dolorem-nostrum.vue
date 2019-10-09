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
      return {"slug":"dolorem-nostrum","name":"Aspernatur consequatur nihil omnis.","description":"Quam vel et. Assumenda aut occaecati. Consequatur ducimus eos.","price":69795.02,"header":"Voluptatem possimus minus sed.","footer":"Rerum quibusdam iste praesentium.","moreInfo":"Voluptates laborum eos omnis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
