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
      return {"slug":"provident-ea","name":"Vero repudiandae consequuntur quae.","description":"Sit soluta ducimus. Eligendi modi mollitia. Veritatis beatae et.","price":61956.07,"header":"Et fugiat necessitatibus velit.","footer":"Mollitia itaque aut voluptas.","moreInfo":"Non explicabo sunt sint."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
