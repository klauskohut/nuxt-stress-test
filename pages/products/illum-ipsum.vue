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
      return {"slug":"illum-ipsum","name":"Incidunt cupiditate repudiandae maiores.","description":"Earum deserunt numquam. Consequatur veniam voluptatem. Ratione perferendis tempora.","price":41889.01,"header":"Ipsam ut quas unde.","footer":"Eaque ex et aliquam.","moreInfo":"Earum amet consequatur aliquam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
