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
      return {"slug":"laborum-omnis","name":"Laboriosam nisi sapiente voluptatem.","description":"Mollitia sunt similique. Et occaecati quia. Ut at sint.","price":48389.86,"header":"Sunt assumenda voluptate maiores.","footer":"Dolores ipsam molestias non.","moreInfo":"Quisquam exercitationem quibusdam et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
