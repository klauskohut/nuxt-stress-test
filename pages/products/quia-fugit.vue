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
      return {"slug":"quia-fugit","name":"Qui aut voluptatum id.","description":"Est consequatur sint. Est fuga et. Temporibus vero maxime.","price":55093.35,"header":"Nemo quas est iste.","footer":"Veniam iste sed dolore.","moreInfo":"Optio reiciendis vitae unde."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
