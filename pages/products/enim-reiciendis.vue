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
      return {"slug":"enim-reiciendis","name":"Quos in officiis voluptas.","description":"Quibusdam quo magni. Incidunt omnis error. Impedit et porro.","price":87490.95,"header":"Perferendis quia est et.","footer":"Quia velit ab sunt.","moreInfo":"Et rerum enim magnam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
