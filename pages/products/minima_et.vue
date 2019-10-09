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
      return {"slug":"minima_et","name":"Praesentium quisquam ex officiis.","description":"Eaque maxime voluptatibus. Voluptas dignissimos at. A odit fugiat.","price":23967.29,"header":"Enim laudantium qui beatae.","footer":"Nihil reiciendis nihil optio.","moreInfo":"Rerum maxime veritatis vero."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
