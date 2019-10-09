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
      return {"slug":"est_est","name":"Quasi dignissimos voluptatibus quos.","description":"Consequatur aut et. Ratione est reiciendis. Est fuga quisquam.","price":50022.48,"header":"Dolore tempora vitae et.","footer":"Reiciendis odio voluptate et.","moreInfo":"Sit saepe quia quidem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
