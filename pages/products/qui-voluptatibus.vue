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
      return {"slug":"qui-voluptatibus","name":"Rerum quisquam laudantium eos.","description":"Deserunt eum ut. Aut nisi accusamus. Eos praesentium rerum.","price":96849.89,"header":"Sequi quis nostrum velit.","footer":"Quam dolores voluptatem nulla.","moreInfo":"Ut amet nesciunt molestias."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
