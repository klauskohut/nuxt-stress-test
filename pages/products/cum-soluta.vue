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
      return {"slug":"cum-soluta","name":"Nihil itaque sed ut.","description":"Fugit qui rerum. Inventore necessitatibus eveniet. Aspernatur enim enim.","price":64578.06,"header":"Consequatur voluptate sed velit.","footer":"Autem culpa hic dolores.","moreInfo":"Excepturi dolores consequatur rerum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
