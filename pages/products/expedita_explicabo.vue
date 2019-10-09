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
      return {"slug":"expedita_explicabo","name":"Voluptatum ratione distinctio non.","description":"Ratione deleniti exercitationem. Magnam repellendus placeat. Et natus quaerat.","price":21361.51,"header":"Excepturi ducimus et et.","footer":"Voluptatum temporibus consequatur et.","moreInfo":"Ipsam similique qui earum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
