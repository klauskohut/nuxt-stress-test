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
      return {"slug":"iure-sunt","name":"Amet soluta earum dolores.","description":"Sed et tempore. Facere ut repellendus. Qui officia voluptas.","price":77982.32,"header":"Accusantium quos pariatur et.","footer":"Et cumque odit maiores.","moreInfo":"Eos harum sed ab."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
