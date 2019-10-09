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
      return {"slug":"aut_numquam","name":"Corrupti necessitatibus fuga asperiores.","description":"Animi occaecati eos. Optio nemo quia. Ex quis ab.","price":30672.62,"header":"Autem aut dignissimos quaerat.","footer":"Aspernatur nostrum est dolor.","moreInfo":"Quos ut pariatur ullam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
