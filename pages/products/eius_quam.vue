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
      return {"slug":"eius_quam","name":"Doloribus omnis et rerum.","description":"Ut fuga nihil. Repellendus qui magnam. Porro tenetur at.","price":71433.17,"header":"Eveniet omnis officiis molestiae.","footer":"Quam necessitatibus beatae occaecati.","moreInfo":"Et molestias et aut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
