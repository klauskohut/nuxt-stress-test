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
      return {"slug":"omnis_velit","name":"Rerum nihil veniam molestiae.","description":"Dolores ullam vel. Exercitationem molestiae ipsam. Pariatur perferendis rerum.","price":71786.31,"header":"Fugiat necessitatibus alias voluptas.","footer":"Sed dignissimos molestiae animi.","moreInfo":"Rerum deleniti accusamus minima."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
