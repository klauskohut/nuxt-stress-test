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
      return {"slug":"soluta-aliquid","name":"Et illo aperiam nemo.","description":"Labore necessitatibus eaque. Qui delectus aperiam. Ut porro tenetur.","price":47564.55,"header":"Sit delectus numquam aut.","footer":"Et ipsum optio aut.","moreInfo":"Beatae aut nisi nihil."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
