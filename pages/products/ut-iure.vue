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
      return {"slug":"ut-iure","name":"Quo non praesentium velit.","description":"Provident consectetur dolorem. In deserunt ut. Aliquid cumque earum.","price":46245.97,"header":"Veniam nam non non.","footer":"Repudiandae sed dolor libero.","moreInfo":"Esse qui voluptatibus rerum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
