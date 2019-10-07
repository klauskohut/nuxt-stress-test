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
      return {"slug":"maxime-nostrum","name":"Sed quia et eveniet.","description":"Temporibus placeat ut. Culpa excepturi perferendis. Voluptatum dolores et.","price":71276.29,"header":"Doloremque libero sint animi.","footer":"Et qui est ut.","moreInfo":"Dicta dolores asperiores ea."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
