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
      return {"slug":"alias_iure","name":"Sint nostrum tempora quae.","description":"Praesentium consequatur neque. Laborum veniam ut. Omnis sit ut.","price":23463.01,"header":"Neque voluptates aliquam dolorum.","footer":"Similique dolorum dolor nostrum.","moreInfo":"Nobis expedita in maxime."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
