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
      return {"slug":"repellendus_porro","name":"Quia perspiciatis pariatur qui.","description":"Nihil praesentium delectus. Quia temporibus iste. Ut ab natus.","price":89923.38,"header":"Amet alias ipsam quod.","footer":"In officiis sed ipsa.","moreInfo":"Et consequatur voluptatem facilis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
