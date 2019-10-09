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
      return {"slug":"quasi_ex","name":"Fugiat fugit cumque quasi.","description":"Voluptatem non cumque. Nihil laudantium voluptas. Ex qui tenetur.","price":54667.54,"header":"Facilis perspiciatis dolorum non.","footer":"Aut tenetur tempora velit.","moreInfo":"Quas officiis similique dolorem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
