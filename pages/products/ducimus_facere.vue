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
      return {"slug":"ducimus_facere","name":"Est sed non fugit.","description":"Aut quas quis. Explicabo sed animi. Id ea nihil.","price":19319.62,"header":"Ipsa perspiciatis molestiae repellat.","footer":"Expedita consequuntur doloremque quaerat.","moreInfo":"Sed et optio perferendis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
