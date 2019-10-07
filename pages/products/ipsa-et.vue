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
      return {"slug":"ipsa-et","name":"Ut at et est.","description":"Itaque unde voluptatem. Autem et ea. Alias similique rerum.","price":76074.64,"header":"Nemo necessitatibus in iste.","footer":"Error expedita qui a.","moreInfo":"Ea veritatis eveniet quia."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
