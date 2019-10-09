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
      return {"slug":"possimus-impedit","name":"Qui rerum ut id.","description":"Explicabo repudiandae qui. Ut animi molestiae. Omnis ipsa vel.","price":65800.48,"header":"Consequuntur omnis error facilis.","footer":"Autem quia sed quisquam.","moreInfo":"Voluptas porro in cumque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
