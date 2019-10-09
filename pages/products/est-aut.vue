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
      return {"slug":"est-aut","name":"Et accusantium reprehenderit incidunt.","description":"Vero quasi earum. Et dolor quod. Ut voluptas sunt.","price":69526.52,"header":"Omnis neque voluptatibus soluta.","footer":"Quas vel ducimus beatae.","moreInfo":"Officia incidunt molestiae voluptatibus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
