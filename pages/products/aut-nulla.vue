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
      return {"slug":"aut-nulla","name":"Et quis aperiam distinctio.","description":"Id repellendus aperiam. Maiores quia est. Ad alias et.","price":63466.83,"header":"Cum natus odit fugiat.","footer":"Ratione magnam velit quasi.","moreInfo":"Qui nisi cupiditate praesentium."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
