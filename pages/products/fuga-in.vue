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
      return {"slug":"fuga-in","name":"Dolorum sint doloribus quis.","description":"Consequatur quam et. Cumque eaque fugit. Quia deleniti voluptate.","price":88447.84,"header":"Vero repellendus minima fuga.","footer":"Distinctio aut illum veniam.","moreInfo":"Voluptatem commodi occaecati ut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
