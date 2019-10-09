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
      return {"slug":"ex-cum","name":"Rerum odit sit placeat.","description":"Officia saepe illo. Dolore est officiis. Illo maiores voluptas.","price":48998.75,"header":"Velit qui non qui.","footer":"Dicta necessitatibus sit quibusdam.","moreInfo":"Et velit optio rem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
