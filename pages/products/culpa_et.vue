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
      return {"slug":"culpa_et","name":"Aut deserunt et error.","description":"Explicabo consequatur nihil. Accusamus soluta nam. Et sint non.","price":59716.75,"header":"Excepturi illum mollitia eligendi.","footer":"Voluptatem aut sapiente molestias.","moreInfo":"Fuga sed delectus ut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
