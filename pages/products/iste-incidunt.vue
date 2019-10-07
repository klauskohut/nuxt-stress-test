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
      return {"slug":"iste-incidunt","name":"Quam accusamus eum est.","description":"Aspernatur id odio. Aliquid sit in. Et suscipit et.","price":69073.85,"header":"Et ut voluptatem sed.","footer":"Dolor harum inventore in.","moreInfo":"Et aut ut distinctio."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
