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
      return {"slug":"voluptatem-eius","name":"Pariatur laboriosam quod repellendus.","description":"Voluptatem iusto dolorum. Dolor sed qui. Aut quo magni.","price":92398.86,"header":"Et illum ut sed.","footer":"Ullam blanditiis sit totam.","moreInfo":"Voluptatem harum nam vel."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
