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
      return {"slug":"rerum-aut","name":"Quasi adipisci perferendis qui.","description":"Rem nobis occaecati. Distinctio quia id. Itaque hic quaerat.","price":32284.45,"header":"Quidem in suscipit voluptatem.","footer":"Voluptatibus aut qui fugiat.","moreInfo":"Expedita dolor iste reprehenderit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
