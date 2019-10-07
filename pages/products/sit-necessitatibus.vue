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
      return {"slug":"sit-necessitatibus","name":"Consequuntur itaque facilis ipsam.","description":"Eveniet architecto veniam. Omnis repellendus corrupti. Aperiam at est.","price":59926.73,"header":"Placeat deserunt voluptates sunt.","footer":"Omnis rerum accusantium quo.","moreInfo":"Et et praesentium fugit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
