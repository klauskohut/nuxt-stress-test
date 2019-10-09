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
      return {"slug":"sit-accusamus","name":"Et quia iusto voluptatem.","description":"Perspiciatis laudantium libero. Natus expedita recusandae. Eius deleniti accusantium.","price":43477.83,"header":"Eos dolores non voluptatem.","footer":"Voluptatibus modi excepturi voluptates.","moreInfo":"Iste quia aut facere."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
