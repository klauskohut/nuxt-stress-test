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
      return {"slug":"facilis-blanditiis","name":"Aut molestias ut officiis.","description":"Pariatur possimus laudantium. Autem eum sed. Et quo sed.","price":77572.53,"header":"Sit aut ut ut.","footer":"Porro aut molestias sint.","moreInfo":"Expedita et neque voluptatem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
