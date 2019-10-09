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
      return {"slug":"aut_inventore","name":"Dolore consequuntur autem rerum.","description":"Quam ut esse. Maxime vel nulla. Consequatur quibusdam sunt.","price":25130.53,"header":"Nobis qui dolorem voluptas.","footer":"Aut similique et minima.","moreInfo":"Totam illo possimus ea."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
