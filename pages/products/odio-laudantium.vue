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
      return {"slug":"odio-laudantium","name":"Et at voluptatem totam.","description":"Illum cumque nulla. Ut et a. Quas temporibus quia.","price":50551.66,"header":"Delectus voluptatem illum ipsam.","footer":"Sed temporibus quos dolor.","moreInfo":"Illo porro est iusto."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
