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
      return {"slug":"id-error","name":"Vel occaecati dolore nostrum.","description":"Quas est nisi. Sint est id. Odit incidunt eveniet.","price":71490.64,"header":"Et quasi consequatur qui.","footer":"Est unde minima quam.","moreInfo":"Doloremque fugiat reiciendis accusantium."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
