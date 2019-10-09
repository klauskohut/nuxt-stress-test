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
      return {"slug":"nihil-consequuntur","name":"Aliquam voluptas eius rem.","description":"Ipsam unde expedita. Libero vero quia. Numquam aspernatur quo.","price":35199.22,"header":"Voluptas et cupiditate molestiae.","footer":"Odit velit et veniam.","moreInfo":"Minima aliquid dicta ut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
