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
      return {"slug":"eius-itaque","name":"Incidunt quis ut vel.","description":"Ut ut consequatur. Unde in est. Ut reprehenderit provident.","price":47416.08,"header":"Sunt commodi iusto dolores.","footer":"Amet non enim sunt.","moreInfo":"Deserunt aut amet atque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
