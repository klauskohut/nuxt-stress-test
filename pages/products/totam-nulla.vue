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
      return {"slug":"totam-nulla","name":"Eaque est sunt blanditiis.","description":"Quisquam voluptates placeat. Ut fugiat accusamus. Tempore voluptate mollitia.","price":37960.53,"header":"Facilis omnis ad et.","footer":"Quis voluptatem molestias ut.","moreInfo":"Sed hic incidunt temporibus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
