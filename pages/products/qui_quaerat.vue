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
      return {"slug":"qui_quaerat","name":"Voluptatem aut debitis veniam.","description":"Ratione excepturi nihil. Accusamus optio quas. Et nesciunt eius.","price":34459.99,"header":"Ut molestiae numquam possimus.","footer":"Repudiandae a expedita nam.","moreInfo":"Quidem cum perferendis similique."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
