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
      return {"slug":"consectetur-minus","name":"Et ex quis et.","description":"Quidem tenetur sunt. Beatae aut praesentium. Possimus est sapiente.","price":42125.63,"header":"Error libero quasi est.","footer":"A qui laudantium velit.","moreInfo":"Dolores rerum molestiae deserunt."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
