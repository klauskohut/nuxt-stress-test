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
      return {"slug":"assumenda-voluptatem","name":"Tenetur dignissimos velit est.","description":"A consectetur tempora. Perspiciatis omnis praesentium. Quo nobis recusandae.","price":56467.76,"header":"Officiis excepturi quia placeat.","footer":"Laudantium tempora et aut.","moreInfo":"Omnis molestias architecto doloribus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
