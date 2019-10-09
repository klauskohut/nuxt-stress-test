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
      return {"slug":"eos_impedit","name":"Sit neque qui est.","description":"Sed illo ratione. Earum dolores qui. Sunt earum laborum.","price":75468.23,"header":"Illum iusto voluptatem reiciendis.","footer":"Est qui hic rem.","moreInfo":"Est modi suscipit ea."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
