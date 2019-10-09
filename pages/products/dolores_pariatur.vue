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
      return {"slug":"dolores_pariatur","name":"Autem omnis magnam qui.","description":"Quidem quia et. Qui hic qui. Consequatur quia qui.","price":10124.77,"header":"In sit et harum.","footer":"Dicta ut maiores quia.","moreInfo":"Ab vel ipsum voluptas."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
