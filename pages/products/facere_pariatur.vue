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
      return {"slug":"facere_pariatur","name":"Quia ratione alias eligendi.","description":"Laboriosam quidem debitis. Nostrum vel optio. Hic provident animi.","price":15689.77,"header":"Non quod odio aut.","footer":"Molestias reiciendis voluptas nihil.","moreInfo":"Ullam sit temporibus ea."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
