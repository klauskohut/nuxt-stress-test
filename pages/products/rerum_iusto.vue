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
      return {"slug":"rerum_iusto","name":"Voluptates aut mollitia laboriosam.","description":"Est corrupti tempore. Alias libero eum. Officiis omnis laborum.","price":32929.86,"header":"Debitis esse quos quaerat.","footer":"Vel minima voluptas alias.","moreInfo":"Neque in corrupti beatae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
