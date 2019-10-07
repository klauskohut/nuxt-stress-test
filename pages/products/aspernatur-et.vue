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
      return {"slug":"aspernatur-et","name":"Eligendi perferendis laudantium mollitia.","description":"Laborum quam ut. Ex accusantium cumque. Cum nemo aut.","price":74873.64,"header":"Et nostrum velit et.","footer":"Ea dignissimos laborum nemo.","moreInfo":"Qui non vel voluptates."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
