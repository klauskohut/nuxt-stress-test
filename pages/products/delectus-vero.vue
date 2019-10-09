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
      return {"slug":"delectus-vero","name":"Rem nam a quo.","description":"Rerum recusandae similique. Placeat voluptas similique. Soluta quis eos.","price":29374.02,"header":"Et voluptatibus soluta modi.","footer":"Asperiores deleniti est placeat.","moreInfo":"Et dolores et rem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
