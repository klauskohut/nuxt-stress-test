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
      return {"slug":"quas-non","name":"Libero quo ut adipisci.","description":"Nobis vitae praesentium. Repudiandae cum ut. Exercitationem alias quis.","price":79263.93,"header":"Doloremque dolores facere animi.","footer":"Perspiciatis molestias non repellendus.","moreInfo":"Qui et voluptatem eum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
