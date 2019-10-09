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
      return {"slug":"eveniet-magnam","name":"Perferendis sequi aut provident.","description":"Nihil unde nostrum. Magnam expedita officia. Accusamus eum quo.","price":84501.24,"header":"Accusantium voluptas maiores itaque.","footer":"Sit velit architecto optio.","moreInfo":"Beatae excepturi eius quae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
