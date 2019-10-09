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
      return {"slug":"ab-porro","name":"Est quidem quasi quia.","description":"Quia labore sit. Veritatis qui illo. Quis doloribus ipsam.","price":99744.33,"header":"Omnis iusto adipisci nihil.","footer":"Culpa corporis impedit dicta.","moreInfo":"In quos et illo."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
