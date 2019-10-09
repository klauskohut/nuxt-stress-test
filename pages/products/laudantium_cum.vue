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
      return {"slug":"laudantium_cum","name":"Pariatur explicabo tempora eum.","description":"Beatae molestias praesentium. Sapiente ut maiores. Nihil voluptatem esse.","price":95137.76,"header":"Blanditiis asperiores optio incidunt.","footer":"Aliquid quis ipsam illo.","moreInfo":"Quam rerum perspiciatis est."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
