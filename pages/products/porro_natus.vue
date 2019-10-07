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
      return {"slug":"porro_natus","name":"Nobis incidunt quos quisquam.","description":"Veniam tempore architecto. Quas debitis rerum. Labore est autem.","price":48941.97,"header":"Rerum et perferendis recusandae.","footer":"Et et voluptatem dolorum.","moreInfo":"Esse voluptas minima recusandae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
