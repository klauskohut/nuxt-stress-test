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
      return {"slug":"incidunt_et","name":"Sint natus aut esse.","description":"Quasi tempore ut. Non maxime aspernatur. Sed qui quibusdam.","price":27678.81,"header":"Maxime quidem architecto eum.","footer":"Sit officia doloribus labore.","moreInfo":"Dolores illum animi quo."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
