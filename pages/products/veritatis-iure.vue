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
      return {"slug":"veritatis-iure","name":"Aspernatur qui dolorum minima.","description":"Sed facilis consequatur. Enim placeat et. Et labore aspernatur.","price":61753.46,"header":"Similique molestiae ut non.","footer":"Sit eligendi dolore et.","moreInfo":"Sunt est quaerat voluptas."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
