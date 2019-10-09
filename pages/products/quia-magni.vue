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
      return {"slug":"quia-magni","name":"Dignissimos est dolores id.","description":"Consequuntur quidem est. Rem optio nam. Rerum doloribus qui.","price":98951.16,"header":"Magnam incidunt quia quasi.","footer":"Est voluptas quia fugiat.","moreInfo":"Error nihil nobis maxime."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
