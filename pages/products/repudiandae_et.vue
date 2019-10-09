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
      return {"slug":"repudiandae_et","name":"Quam omnis aut facere.","description":"Doloribus atque consequatur. Eum harum aut. Omnis ea et.","price":27426.86,"header":"Omnis non veniam necessitatibus.","footer":"Ratione est soluta molestiae.","moreInfo":"Vitae fugiat unde dolore."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
