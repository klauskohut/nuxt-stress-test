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
      return {"slug":"aut_aut","name":"Voluptas quas nisi dicta.","description":"Officiis autem voluptatem. Delectus tempora dolorum. Quia sed et.","price":57196.61,"header":"Aliquam ea adipisci nesciunt.","footer":"Reiciendis nulla voluptatem sapiente.","moreInfo":"Sunt sed et atque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
