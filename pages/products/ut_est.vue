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
      return {"slug":"ut_est","name":"Ipsam sed in blanditiis.","description":"Velit omnis nihil. Velit voluptate harum. Libero consectetur aut.","price":98384.21,"header":"Consectetur est velit porro.","footer":"Tempore numquam dolores eaque.","moreInfo":"Corporis est et repellendus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
