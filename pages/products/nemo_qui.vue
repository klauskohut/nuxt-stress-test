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
      return {"slug":"nemo_qui","name":"Hic harum quia enim.","description":"Non dolorem qui. Error ut officia. Fugiat libero beatae.","price":78297.13,"header":"Aut qui ut tempore.","footer":"Sit ratione ullam labore.","moreInfo":"Voluptatem ut minima ipsam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
