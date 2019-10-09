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
      return {"slug":"excepturi_est","name":"At sit quibusdam doloremque.","description":"Rerum totam voluptas. Praesentium eligendi autem. Et amet quisquam.","price":66190.51,"header":"Ea veniam ipsum qui.","footer":"Delectus dolorem et sint.","moreInfo":"Error ullam non velit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
