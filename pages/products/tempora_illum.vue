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
      return {"slug":"tempora_illum","name":"Nihil aspernatur molestiae aliquam.","description":"Ut enim quo. Veniam est tempore. Et cupiditate molestiae.","price":83978.21,"header":"Eveniet porro alias aspernatur.","footer":"Placeat nam ipsa sint.","moreInfo":"Quis voluptatem quia corrupti."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
