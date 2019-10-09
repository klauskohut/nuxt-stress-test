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
      return {"slug":"quae_ipsam","name":"Distinctio quis nobis unde.","description":"Porro perspiciatis est. Tempora ad aut. Molestiae ut amet.","price":73873.85,"header":"Accusamus illo porro cumque.","footer":"Fuga et voluptas ex.","moreInfo":"Aut corporis voluptatem pariatur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
