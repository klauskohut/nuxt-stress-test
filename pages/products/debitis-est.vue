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
      return {"slug":"debitis-est","name":"Qui ex quod architecto.","description":"Tempora doloribus accusamus. Voluptatem facilis optio. Ea quia et.","price":17057.82,"header":"Recusandae cum mollitia at.","footer":"Qui deserunt dolor eius.","moreInfo":"Est dolorum esse et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
