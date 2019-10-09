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
      return {"slug":"vero-quos","name":"Recusandae nam aut voluptatibus.","description":"Doloremque dolor nihil. Ratione quidem consequatur. Est molestiae placeat.","price":57184.84,"header":"Dolorem voluptatum sint rem.","footer":"Et dolorum cumque similique.","moreInfo":"Consequatur minus atque sunt."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
