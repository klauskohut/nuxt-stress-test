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
      return {"slug":"cupiditate_tempora","name":"Fuga ut et quas.","description":"Suscipit optio temporibus. Voluptatem mollitia eius. Et nobis qui.","price":61441.21,"header":"Sunt aspernatur magnam et.","footer":"Voluptatem aut dolor voluptatem.","moreInfo":"Quia ad tenetur quisquam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
