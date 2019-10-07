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
      return {"slug":"debitis_rem","name":"Perspiciatis distinctio occaecati et.","description":"Rerum omnis totam. Esse distinctio aut. Ratione non rerum.","price":54097.09,"header":"Nihil corporis fuga ratione.","footer":"Debitis maxime deleniti non.","moreInfo":"Rerum laborum qui alias."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
