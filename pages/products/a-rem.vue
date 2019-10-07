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
      return {"slug":"a-rem","name":"Temporibus aliquam officiis quia.","description":"Possimus aut perferendis. Sapiente facilis molestias. Illo et deleniti.","price":46138.33,"header":"Doloribus iusto occaecati consequatur.","footer":"Quia tenetur doloremque deleniti.","moreInfo":"Impedit iste molestiae quia."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
