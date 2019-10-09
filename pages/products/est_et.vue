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
      return {"slug":"est_et","name":"Est occaecati eos omnis.","description":"Nostrum culpa et. Sed rem autem. Omnis totam culpa.","price":25279.06,"header":"Eum cum fugiat architecto.","footer":"Fugit eum incidunt doloremque.","moreInfo":"Cum reiciendis reprehenderit iure."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
