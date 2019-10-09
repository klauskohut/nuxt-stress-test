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
      return {"slug":"vel-deleniti","name":"Consequatur qui sed cum.","description":"Dolor perferendis incidunt. Consequatur aliquam nostrum. Id blanditiis odio.","price":31512.87,"header":"Earum vel ex consequatur.","footer":"Ab esse quis et.","moreInfo":"Repudiandae qui a qui."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
