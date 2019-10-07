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
      return {"slug":"harum-sit","name":"Ad incidunt et aut.","description":"Numquam rerum velit. Molestiae nisi voluptatibus. Occaecati temporibus sed.","price":48732.11,"header":"Ut rerum et praesentium.","footer":"Ut quod magni dolorem.","moreInfo":"Deserunt incidunt laborum et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
