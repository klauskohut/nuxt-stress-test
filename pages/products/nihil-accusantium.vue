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
      return {"slug":"nihil-accusantium","name":"Omnis totam dolores nesciunt.","description":"Quis provident error. Distinctio voluptatem qui. Ea autem eligendi.","price":87568.92,"header":"Cumque culpa sint reprehenderit.","footer":"Accusamus debitis vel possimus.","moreInfo":"Est nostrum voluptatem laboriosam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
