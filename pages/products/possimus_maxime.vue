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
      return {"slug":"possimus_maxime","name":"Officiis sit voluptatum et.","description":"Vero ea atque. Consectetur quia aut. Ex dignissimos illo.","price":18155.67,"header":"Quae quidem nobis deleniti.","footer":"Qui totam expedita dolore.","moreInfo":"Omnis cupiditate non blanditiis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
