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
      return {"slug":"consequuntur_quia","name":"Minima fuga dolor rem.","description":"Et et in. Maxime quod sapiente. Hic tempora odit.","price":54473.04,"header":"Aut est quidem et.","footer":"Quasi autem in perferendis.","moreInfo":"Delectus corporis maiores harum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
