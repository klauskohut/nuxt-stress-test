<template>
  <Product :slug="slug" :name="name" :description="description" :price="price" :header="header" :footer="footer">
    <h3>More product info below:</h3>
    <p>{{moreInfo}}</p>
  </Product>
</template>

<script>
  import Product from '../product'
  export default {
    layout: 'product',
    components: {
      Product,
    },
    data() {
      return {"slug":"architecto_voluptas","name":"Fugit eos pariatur doloribus.","description":"Eligendi error aut. Sed ea ut. Aut ducimus accusantium.","price":88591.22,"header":"In ducimus odit omnis.","footer":"Molestias totam repudiandae dolor.","moreInfo":"Non voluptatem vel et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
