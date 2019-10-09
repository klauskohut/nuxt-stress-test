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
      return {"slug":"alias-molestiae","name":"Illo est rerum in.","description":"Perferendis autem provident. Nisi voluptas voluptate. Id et et.","price":37323.59,"header":"Qui maiores labore eos.","footer":"Earum omnis ducimus rerum.","moreInfo":"Voluptatem omnis nam voluptatem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
