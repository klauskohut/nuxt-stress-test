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
      return {"slug":"repudiandae_mollitia","name":"Qui similique sit necessitatibus.","description":"Fuga voluptatem enim. Tempore quo et. Dolores nisi vel.","price":88623.86,"header":"Harum praesentium a ipsam.","footer":"Eius odio accusamus eligendi.","moreInfo":"Sint pariatur alias ipsum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
