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
      return {"slug":"et-aspernatur","name":"Porro iste qui ipsa.","description":"Laboriosam sed architecto. Et doloribus eos. Tempora laudantium perferendis.","price":41285.33,"header":"Ut omnis soluta eum.","footer":"Consequatur sed consequatur est.","moreInfo":"Quidem cupiditate qui odit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
