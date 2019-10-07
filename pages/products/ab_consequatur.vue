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
      return {"slug":"ab_consequatur","name":"Ut enim incidunt sit.","description":"Magnam tempore sit. Dolores enim officiis. Ut laudantium quae.","price":30742.06,"header":"At dolor incidunt sit.","footer":"In necessitatibus amet qui.","moreInfo":"Iste quae fugit libero."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
