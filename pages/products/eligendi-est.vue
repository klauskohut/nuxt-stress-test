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
      return {"slug":"eligendi-est","name":"Aperiam qui excepturi aut.","description":"Fuga laborum itaque. Non veniam cupiditate. Debitis quos quisquam.","price":99834.67,"header":"Qui nihil nesciunt qui.","footer":"Autem quisquam assumenda adipisci.","moreInfo":"Voluptates est in voluptate."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
