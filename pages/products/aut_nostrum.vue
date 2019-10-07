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
      return {"slug":"aut_nostrum","name":"Modi corrupti nisi cupiditate.","description":"Corporis sint quibusdam. Illo nulla voluptate. Voluptate rerum vel.","price":57082.92,"header":"Consequatur suscipit quo inventore.","footer":"Laudantium et aspernatur modi.","moreInfo":"Delectus et consequatur id."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
