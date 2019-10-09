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
      return {"slug":"eos_est","name":"Quo ratione eum corrupti.","description":"Quis sapiente iusto. Facere a expedita. Quo amet necessitatibus.","price":22575.79,"header":"Quae non voluptas voluptatem.","footer":"Aut nihil sunt eum.","moreInfo":"Sed sed explicabo quidem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
