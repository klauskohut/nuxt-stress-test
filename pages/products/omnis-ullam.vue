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
      return {"slug":"omnis-ullam","name":"Beatae ea cum doloribus.","description":"Molestiae sit aperiam. Voluptas dolores ullam. Earum aut delectus.","price":19621.55,"header":"Rerum pariatur quo nobis.","footer":"Eveniet beatae impedit sequi.","moreInfo":"Reiciendis nihil quis qui."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
