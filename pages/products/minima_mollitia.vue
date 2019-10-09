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
      return {"slug":"minima_mollitia","name":"Beatae sed optio maxime.","description":"Ex omnis et. Et occaecati quo. Reprehenderit facere totam.","price":61187.09,"header":"Mollitia dolorum expedita repellendus.","footer":"Numquam deleniti nihil quos.","moreInfo":"Officia enim ipsam ea."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
