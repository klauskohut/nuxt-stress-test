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
      return {"slug":"a-impedit","name":"Earum ut impedit ipsum.","description":"Consequatur accusantium magni. Porro et velit. Facere illo mollitia.","price":23248.76,"header":"Fugit est ratione itaque.","footer":"Magnam qui voluptatibus aut.","moreInfo":"Voluptates voluptas earum rerum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
