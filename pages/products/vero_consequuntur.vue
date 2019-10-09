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
      return {"slug":"vero_consequuntur","name":"Expedita aut ut tenetur.","description":"Magni animi nulla. Sunt voluptatem qui. Id fugit laboriosam.","price":70867.76,"header":"Molestiae sint eligendi quis.","footer":"Modi sunt reprehenderit doloribus.","moreInfo":"Voluptatem eos inventore nobis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
