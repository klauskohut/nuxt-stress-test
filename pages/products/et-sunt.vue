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
      return {"slug":"et-sunt","name":"Qui error modi distinctio.","description":"Laudantium perferendis ut. Rerum nulla labore. Soluta quas pariatur.","price":42150.34,"header":"Omnis quae suscipit aut.","footer":"Non culpa est tempore.","moreInfo":"Omnis repudiandae sapiente qui."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
