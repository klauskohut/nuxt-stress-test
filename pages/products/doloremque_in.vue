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
      return {"slug":"doloremque_in","name":"Iure vel iste architecto.","description":"Vero et fugiat. Enim aut perspiciatis. Dolorem qui quis.","price":43700.97,"header":"Corrupti quaerat labore eligendi.","footer":"Fuga non totam explicabo.","moreInfo":"Molestias nihil voluptatibus corporis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
