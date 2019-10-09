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
      return {"slug":"earum-occaecati","name":"Eaque ut dolorum consequatur.","description":"Nostrum officiis minima. Recusandae vero culpa. Voluptates illo quia.","price":26719.31,"header":"Quo et veritatis ea.","footer":"Odio et repellendus libero.","moreInfo":"Molestias voluptatem quos voluptatem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
