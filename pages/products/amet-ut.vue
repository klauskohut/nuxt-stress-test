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
      return {"slug":"amet-ut","name":"Quia vel hic rerum.","description":"Sed minima esse. Aut nulla culpa. In ut provident.","price":20811.63,"header":"Accusantium delectus qui vitae.","footer":"Veritatis ut expedita eligendi.","moreInfo":"Quibusdam consequatur sed quae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
