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
      return {"slug":"magni-accusantium","name":"Voluptatem vel quibusdam voluptatem.","description":"Consequatur aut sapiente. Aliquid eaque quis. Et quia aut.","price":42888.22,"header":"Autem distinctio ut iure.","footer":"Voluptatem voluptatem illo quis.","moreInfo":"Molestiae in eos ab."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
