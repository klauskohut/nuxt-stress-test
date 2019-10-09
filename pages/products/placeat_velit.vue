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
      return {"slug":"placeat_velit","name":"Minima earum aut ut.","description":"Velit animi cupiditate. Eius consequuntur voluptatem. Totam dolores ducimus.","price":96479.93,"header":"Optio ut exercitationem officia.","footer":"Aut eaque enim quia.","moreInfo":"Cum quae pariatur id."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
