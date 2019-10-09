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
      return {"slug":"maxime-provident","name":"Officiis ad esse dolores.","description":"Asperiores deserunt provident. Est nemo suscipit. Nihil vero nulla.","price":54327.24,"header":"Suscipit quis molestiae aspernatur.","footer":"Perferendis delectus laudantium autem.","moreInfo":"Voluptatem maiores ut facere."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
