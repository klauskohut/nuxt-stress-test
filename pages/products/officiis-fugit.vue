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
      return {"slug":"officiis-fugit","name":"Vitae ea animi et.","description":"Fuga sunt omnis. Vel et eaque. Provident aspernatur illum.","price":35291.28,"header":"Ducimus doloribus est vero.","footer":"Cumque nam veniam architecto.","moreInfo":"Error aut est debitis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
