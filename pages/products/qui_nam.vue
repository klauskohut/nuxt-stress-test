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
      return {"slug":"qui_nam","name":"Impedit unde exercitationem sint.","description":"Qui sapiente provident. Rerum molestiae commodi. Et ipsam earum.","price":57393.87,"header":"Voluptatem ut qui maxime.","footer":"Sunt occaecati consectetur itaque.","moreInfo":"Ut omnis autem in."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
