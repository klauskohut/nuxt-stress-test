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
      return {"slug":"ullam_maiores","name":"Optio qui nobis ratione.","description":"Molestias nihil quia. Deleniti unde tempore. Voluptatem id labore.","price":79534.61,"header":"Voluptatem laborum molestiae dolores.","footer":"Ad est quo excepturi.","moreInfo":"Ipsam vel beatae nobis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
