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
      return {"slug":"mollitia-aut","name":"Quasi sed cum cumque.","description":"Laboriosam qui possimus. Consequatur non culpa. Et est dolore.","price":14667.05,"header":"Aut a cupiditate dicta.","footer":"Consectetur labore quia aspernatur.","moreInfo":"Enim officiis provident deleniti."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
