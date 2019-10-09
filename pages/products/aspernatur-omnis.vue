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
      return {"slug":"aspernatur-omnis","name":"Perferendis qui voluptatum earum.","description":"Minima quam sed. Fuga maxime et. Qui minus omnis.","price":72407.96,"header":"Dolores expedita voluptates beatae.","footer":"Laudantium ut nam placeat.","moreInfo":"Modi molestiae aut sed."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
