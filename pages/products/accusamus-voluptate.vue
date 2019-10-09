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
      return {"slug":"accusamus-voluptate","name":"Voluptates voluptas excepturi nisi.","description":"Nam corrupti voluptatem. Nesciunt omnis sit. Vel sed ea.","price":40457.72,"header":"Consequatur hic perspiciatis dolorum.","footer":"Enim voluptatem et sit.","moreInfo":"Autem velit animi aperiam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
