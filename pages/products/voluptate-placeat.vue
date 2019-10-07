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
      return {"slug":"voluptate-placeat","name":"Soluta vel reprehenderit similique.","description":"Esse laudantium sunt. Reiciendis labore nisi. Et deserunt quia.","price":38987.48,"header":"Nihil veniam quaerat molestiae.","footer":"Sequi ipsa voluptates delectus.","moreInfo":"Aut eius iste distinctio."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
