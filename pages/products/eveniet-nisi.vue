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
      return {"slug":"eveniet-nisi","name":"Rerum saepe ipsum qui.","description":"Et dolor est. Et nihil dolor. Cupiditate nisi modi.","price":75573.15,"header":"Facere vitae quo voluptas.","footer":"Eius rem architecto nemo.","moreInfo":"Atque dolores eos est."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
