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
      return {"slug":"excepturi_sed","name":"Quo tempora doloribus harum.","description":"Dicta sit animi. Laboriosam delectus ratione. Nemo velit dolore.","price":17390.03,"header":"Error cumque qui eius.","footer":"Eveniet deserunt vel enim.","moreInfo":"Saepe consequatur est aut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
