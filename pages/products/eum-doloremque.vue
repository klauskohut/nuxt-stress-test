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
      return {"slug":"eum-doloremque","name":"Possimus corporis et neque.","description":"Suscipit voluptatem itaque. Provident libero fugit. Ducimus molestiae vel.","price":48732.11,"header":"Saepe aut molestias tenetur.","footer":"Optio et illum officiis.","moreInfo":"Provident quia ullam voluptatum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
