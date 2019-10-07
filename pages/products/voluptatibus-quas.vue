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
      return {"slug":"voluptatibus-quas","name":"Et rerum ea voluptate.","description":"Sunt ut quos. Ea ullam quidem. Non assumenda quam.","price":88557.22,"header":"Aperiam fuga vel nulla.","footer":"Nihil doloribus temporibus ratione.","moreInfo":"Error quibusdam aut voluptatibus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
