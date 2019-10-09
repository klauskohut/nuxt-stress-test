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
      return {"slug":"veniam-minus","name":"Consequatur et deserunt quidem.","description":"Eius distinctio rerum. Aspernatur iure ad. Vero dolorum autem.","price":87391.54,"header":"Laudantium facere repellendus et.","footer":"Occaecati maiores nostrum vel.","moreInfo":"Distinctio eos sunt aspernatur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
