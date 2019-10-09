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
      return {"slug":"ab_omnis","name":"Similique consequatur quam sint.","description":"Error in impedit. Iure eum cupiditate. Quis aspernatur nesciunt.","price":51280.39,"header":"Incidunt non tenetur qui.","footer":"Explicabo cumque consequuntur voluptas.","moreInfo":"Voluptate provident placeat incidunt."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
