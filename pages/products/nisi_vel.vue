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
      return {"slug":"nisi_vel","name":"Voluptates deleniti quis distinctio.","description":"Ut ab cum. Sit architecto voluptatem. Quae hic ut.","price":62757.52,"header":"Quasi illum pariatur blanditiis.","footer":"Architecto et eaque quod.","moreInfo":"Vel facilis tenetur quidem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
