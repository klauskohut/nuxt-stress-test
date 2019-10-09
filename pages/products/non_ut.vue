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
      return {"slug":"non_ut","name":"Molestiae omnis ipsum tempore.","description":"Voluptatibus repudiandae consectetur. Temporibus est sapiente. Quam reiciendis illo.","price":60617.53,"header":"Et rem quo quia.","footer":"Placeat dicta ut beatae.","moreInfo":"Et consequatur rem harum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
