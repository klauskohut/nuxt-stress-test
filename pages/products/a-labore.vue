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
      return {"slug":"a-labore","name":"Voluptatem beatae suscipit architecto.","description":"Itaque in officia. Est saepe assumenda. Illum aspernatur molestiae.","price":84020.25,"header":"Natus nostrum et dolorem.","footer":"Eum tempore ut quidem.","moreInfo":"Molestiae mollitia accusamus nobis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
