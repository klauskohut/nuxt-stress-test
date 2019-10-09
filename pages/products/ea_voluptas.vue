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
      return {"slug":"ea_voluptas","name":"Officiis consectetur qui ipsum.","description":"Voluptates voluptate quaerat. Velit beatae quia. Dolor eum qui.","price":88039.06,"header":"Delectus sequi quae qui.","footer":"Hic sunt rerum sed.","moreInfo":"Aliquid voluptatem rerum sit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
