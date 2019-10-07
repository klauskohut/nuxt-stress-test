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
      return {"slug":"autem-eligendi","name":"Quod nisi voluptas quae.","description":"Sit officiis necessitatibus. Sequi a doloribus. Repellendus cumque amet.","price":94961.13,"header":"Architecto voluptas corporis sint.","footer":"Sint aperiam natus distinctio.","moreInfo":"Distinctio laudantium ea aspernatur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
