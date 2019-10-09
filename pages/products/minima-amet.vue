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
      return {"slug":"minima-amet","name":"Libero esse quasi facere.","description":"Optio sit voluptatem. Nihil vero porro. Natus nisi qui.","price":59109.01,"header":"Eos ut maiores mollitia.","footer":"Minus iure perspiciatis placeat.","moreInfo":"Nihil et est praesentium."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
