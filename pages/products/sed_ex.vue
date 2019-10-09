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
      return {"slug":"sed_ex","name":"Tempora aperiam quibusdam suscipit.","description":"At sit quibusdam. Animi perferendis ad. Ut fugiat saepe.","price":47032.64,"header":"Voluptatibus enim accusamus autem.","footer":"Vel nulla consequatur voluptate.","moreInfo":"Eum est quia consequatur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
