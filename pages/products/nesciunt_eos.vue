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
      return {"slug":"nesciunt_eos","name":"Est eos suscipit voluptatem.","description":"Ipsa qui sunt. Et culpa quae. Consequatur quasi in.","price":47837.79,"header":"Et repudiandae nisi tenetur.","footer":"Omnis unde delectus necessitatibus.","moreInfo":"A voluptatibus at et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
