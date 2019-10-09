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
      return {"slug":"consequuntur-ut","name":"Atque nam eaque et.","description":"Animi sit facere. Pariatur totam ea. Architecto quis commodi.","price":58499.72,"header":"Pariatur reprehenderit recusandae maiores.","footer":"Facilis numquam et architecto.","moreInfo":"Et neque enim vitae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
