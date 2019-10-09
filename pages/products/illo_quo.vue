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
      return {"slug":"illo_quo","name":"Explicabo voluptate nam eligendi.","description":"Et quo optio. Nostrum libero aut. Et qui maxime.","price":56188.84,"header":"Sit consectetur non rerum.","footer":"Iusto sunt saepe quod.","moreInfo":"Ut architecto porro ut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
