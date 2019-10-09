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
      return {"slug":"facere_non","name":"Quis ex beatae aut.","description":"Animi qui exercitationem. Sed fuga praesentium. Veritatis amet qui.","price":97088.06,"header":"Omnis rem reprehenderit nostrum.","footer":"Voluptatem nulla aut nisi.","moreInfo":"Numquam ea iure deserunt."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
