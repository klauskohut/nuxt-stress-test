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
      return {"slug":"nulla_sapiente","name":"Deleniti officia facere quaerat.","description":"Itaque culpa reprehenderit. Voluptas doloremque magnam. Sunt culpa quia.","price":32324.39,"header":"Quia ipsam ipsum ducimus.","footer":"Libero quasi ut doloremque.","moreInfo":"Deserunt excepturi labore vel."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
