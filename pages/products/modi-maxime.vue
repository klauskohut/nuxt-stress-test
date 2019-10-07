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
      return {"slug":"modi-maxime","name":"Aliquid dolore magni sint.","description":"Doloribus voluptas reprehenderit. Ab voluptates sit. Voluptates est veritatis.","price":44588.31,"header":"Et incidunt in possimus.","footer":"Rerum dolore debitis explicabo.","moreInfo":"Placeat rerum quos excepturi."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
