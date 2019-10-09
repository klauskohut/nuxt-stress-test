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
      return {"slug":"sit-cupiditate","name":"Eligendi assumenda numquam aliquid.","description":"Architecto et aut. Ullam voluptas deleniti. Aliquid consequatur et.","price":54901.32,"header":"Ut harum et dolore.","footer":"Non eum quasi aliquam.","moreInfo":"Adipisci fuga ut nam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
