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
      return {"slug":"rerum-perspiciatis","name":"Sit debitis impedit et.","description":"Qui fugiat enim. Quo debitis aut. Placeat deserunt dolores.","price":18220.13,"header":"Laudantium quisquam voluptas nihil.","footer":"Natus cum ut recusandae.","moreInfo":"Voluptatem id eveniet repudiandae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
