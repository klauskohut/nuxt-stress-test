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
      return {"slug":"officiis_repellat","name":"Est odit deleniti id.","description":"Voluptates minus culpa. Et placeat atque. Maiores corporis et.","price":32857.95,"header":"Qui laudantium dolore ipsam.","footer":"Sit rerum quae neque.","moreInfo":"Id nisi magni quia."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
