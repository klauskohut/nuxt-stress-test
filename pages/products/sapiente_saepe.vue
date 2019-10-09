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
      return {"slug":"sapiente_saepe","name":"Quasi tenetur ut qui.","description":"Ut non est. Officiis ea at. Laborum eum dolorum.","price":98334.11,"header":"Sint ipsa cupiditate delectus.","footer":"Nihil perferendis eaque cumque.","moreInfo":"Sapiente autem autem magnam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
