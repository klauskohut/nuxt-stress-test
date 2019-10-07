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
      return {"slug":"aut-porro","name":"Architecto ipsa sit minus.","description":"Quasi voluptatum aut. Repellendus et eligendi. Et magnam et.","price":89073.35,"header":"Quasi sit soluta a.","footer":"Sit voluptas voluptatem ipsa.","moreInfo":"Sapiente a debitis velit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
