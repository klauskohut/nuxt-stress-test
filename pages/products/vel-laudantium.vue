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
      return {"slug":"vel-laudantium","name":"Ut assumenda impedit accusamus.","description":"Eius quia id. Pariatur enim aut. Repellendus ut sapiente.","price":37751.57,"header":"Laboriosam voluptatum nulla hic.","footer":"Dicta voluptates eveniet nulla.","moreInfo":"Harum delectus est quia."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
