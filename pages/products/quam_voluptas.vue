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
      return {"slug":"quam_voluptas","name":"Et culpa ipsum ut.","description":"Sint quasi cum. Omnis aut voluptate. Reprehenderit animi ut.","price":27850.61,"header":"Vel eaque voluptatem aut.","footer":"Et aspernatur sit consequuntur.","moreInfo":"Vitae ea animi eaque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
