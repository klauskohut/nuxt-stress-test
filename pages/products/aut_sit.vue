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
      return {"slug":"aut_sit","name":"Et nam eligendi molestiae.","description":"Minima quis velit. A laboriosam laborum. Dicta blanditiis eum.","price":13788.11,"header":"Aut incidunt exercitationem eum.","footer":"Possimus deleniti fugiat deserunt.","moreInfo":"Magni beatae fugit ex."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
