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
      return {"slug":"itaque-necessitatibus","name":"Fugit adipisci magni delectus.","description":"Velit sint possimus. Voluptas minus consequuntur. Cum rerum fugiat.","price":52196.75,"header":"Unde sequi natus qui.","footer":"Quo sapiente blanditiis unde.","moreInfo":"Ut facilis qui ad."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
