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
      return {"slug":"porro-nulla","name":"Dolores vero enim sint.","description":"Velit dolores ut. Qui est illo. Recusandae dolor ab.","price":10724.82,"header":"Repudiandae illum qui at.","footer":"Ut excepturi recusandae occaecati.","moreInfo":"Voluptate facilis illo incidunt."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
