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
      return {"slug":"mollitia_quibusdam","name":"Qui dolorum quia error.","description":"Vel ut cupiditate. Iure repellat distinctio. Est vitae voluptates.","price":41661.07,"header":"Cum ipsa esse adipisci.","footer":"Omnis ea iure est.","moreInfo":"Aut mollitia occaecati omnis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
