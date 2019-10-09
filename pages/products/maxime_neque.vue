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
      return {"slug":"maxime_neque","name":"Aut recusandae quia explicabo.","description":"Similique distinctio in. Enim qui distinctio. Sed est placeat.","price":29320.27,"header":"Est optio quo voluptatem.","footer":"Veritatis ut qui et.","moreInfo":"Nesciunt voluptate laudantium error."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
