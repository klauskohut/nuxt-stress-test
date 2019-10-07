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
      return {"slug":"quas-labore","name":"Enim sint totam delectus.","description":"Et sit debitis. Maxime assumenda animi. Est dolor harum.","price":86533.85,"header":"Facere quisquam enim et.","footer":"Quos consequatur ut eligendi.","moreInfo":"Earum distinctio autem iure."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
