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
      return {"slug":"libero-odit","name":"Soluta tempora et ipsam.","description":"Culpa accusamus enim. Incidunt velit inventore. Quidem corrupti non.","price":37656.89,"header":"Dolores perspiciatis consequatur ut.","footer":"Deserunt sunt non modi.","moreInfo":"Modi perferendis nisi quibusdam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
