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
      return {"slug":"omnis_mollitia","name":"Rerum autem et soluta.","description":"Totam quasi ducimus. Qui et ut. Nemo optio doloremque.","price":21862.49,"header":"Aut consequuntur iusto unde.","footer":"Doloremque esse dolorum quo.","moreInfo":"Fugit et ea quo."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
