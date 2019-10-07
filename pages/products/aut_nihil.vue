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
      return {"slug":"aut_nihil","name":"Corporis et dolores quia.","description":"Voluptas alias maxime. Harum dicta explicabo. In et modi.","price":94666.42,"header":"A qui aut rerum.","footer":"Officiis in omnis consequuntur.","moreInfo":"Impedit possimus architecto odit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
