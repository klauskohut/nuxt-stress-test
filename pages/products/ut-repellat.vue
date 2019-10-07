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
      return {"slug":"ut-repellat","name":"Esse ea ullam sit.","description":"Tenetur saepe rerum. Et est eum. Sunt labore sit.","price":23826.88,"header":"Ab consequatur culpa omnis.","footer":"Sed tempora fugit nesciunt.","moreInfo":"Ullam voluptates id qui."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
