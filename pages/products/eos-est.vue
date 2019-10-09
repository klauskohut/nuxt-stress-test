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
      return {"slug":"eos-est","name":"Aut rerum officiis fuga.","description":"Architecto debitis rerum. Ea doloribus voluptatibus. Quis dolores porro.","price":37870.22,"header":"Veniam aperiam maiores explicabo.","footer":"Odio possimus ut similique.","moreInfo":"Incidunt repellendus sed quo."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
