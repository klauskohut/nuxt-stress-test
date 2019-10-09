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
      return {"slug":"in_deleniti","name":"Aut qui tempore quas.","description":"Nihil sunt rem. Fugit ut ad. Qui blanditiis maxime.","price":72385.97,"header":"Vel dolor nostrum minus.","footer":"Labore quod modi ea.","moreInfo":"Architecto nisi doloremque laborum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
