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
      return {"slug":"laborum_vel","name":"Consectetur quo ea reiciendis.","description":"Voluptate vitae culpa. Delectus aperiam necessitatibus. Qui quo dolores.","price":61969.86,"header":"Velit accusantium id enim.","footer":"Repellat sit qui facere.","moreInfo":"Non aspernatur rerum et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
