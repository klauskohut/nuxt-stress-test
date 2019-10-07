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
      return {"slug":"ut-necessitatibus","name":"Est occaecati et earum.","description":"Voluptate suscipit sit. Soluta velit veniam. Et quo nam.","price":39923.89,"header":"Explicabo sed eligendi est.","footer":"Quis ab a qui.","moreInfo":"Occaecati inventore eum praesentium."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
