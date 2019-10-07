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
      return {"slug":"qui-id","name":"Natus molestiae nulla nostrum.","description":"Repudiandae et voluptatem. Eos repellendus in. Ratione aut ab.","price":73468.22,"header":"Suscipit laudantium sed est.","footer":"Error quia sit assumenda.","moreInfo":"Sint necessitatibus et ut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
