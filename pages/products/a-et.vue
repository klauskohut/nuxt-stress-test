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
      return {"slug":"a-et","name":"Et qui maiores doloremque.","description":"Qui id neque. Facere ipsam sit. Deleniti nostrum dicta.","price":27446.42,"header":"In sapiente iusto et.","footer":"Facere necessitatibus mollitia et.","moreInfo":"Quia quia et et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
