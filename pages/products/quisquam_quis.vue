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
      return {"slug":"quisquam_quis","name":"Nam enim nesciunt suscipit.","description":"Atque similique voluptate. At nemo consequatur. Qui laudantium sunt.","price":30641.33,"header":"In fuga minus fugit.","footer":"Deserunt vel quis reiciendis.","moreInfo":"Ipsa possimus sed et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
