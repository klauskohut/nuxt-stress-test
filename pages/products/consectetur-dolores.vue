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
      return {"slug":"consectetur-dolores","name":"Odit minima aperiam aut.","description":"Est voluptates enim. Quo nihil laudantium. Cupiditate velit est.","price":53755.01,"header":"Atque cum culpa dolorum.","footer":"Qui sint repellat voluptatibus.","moreInfo":"Nihil molestias et aliquid."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
