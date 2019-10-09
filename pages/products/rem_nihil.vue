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
      return {"slug":"rem_nihil","name":"Excepturi dolor placeat nihil.","description":"Voluptates omnis ipsum. Exercitationem saepe porro. Neque facere explicabo.","price":13356.25,"header":"Quibusdam illum sequi culpa.","footer":"Et itaque non magnam.","moreInfo":"Placeat voluptas possimus id."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
