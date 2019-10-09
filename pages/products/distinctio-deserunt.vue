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
      return {"slug":"distinctio-deserunt","name":"Dolorum facere nam quasi.","description":"Eius et quod. Nemo deleniti quidem. Autem id consequatur.","price":57959.71,"header":"Harum soluta alias dolorum.","footer":"Facere consequatur facilis dolores.","moreInfo":"Debitis sint praesentium veritatis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
