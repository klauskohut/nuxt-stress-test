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
      return {"slug":"iure-natus","name":"Voluptates omnis et dolorem.","description":"Dicta repellendus molestiae. Culpa non modi. Ut consequatur sit.","price":48787.11,"header":"Quisquam vero explicabo ut.","footer":"Accusamus et et quasi.","moreInfo":"Dolore ea totam esse."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
