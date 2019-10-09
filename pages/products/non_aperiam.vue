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
      return {"slug":"non_aperiam","name":"Quaerat velit molestias sint.","description":"Qui consequatur dolorem. Est laborum omnis. Qui provident temporibus.","price":91563.76,"header":"Non eveniet ipsam aliquam.","footer":"Ipsa inventore excepturi harum.","moreInfo":"Modi itaque molestias molestiae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
