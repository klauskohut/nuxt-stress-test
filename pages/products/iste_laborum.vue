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
      return {"slug":"iste_laborum","name":"Aut maiores quam quae.","description":"Consequatur quasi quas. Voluptatem quibusdam recusandae. Dolore quas impedit.","price":64160.41,"header":"Quae qui totam ipsam.","footer":"Quos ab neque quisquam.","moreInfo":"Reprehenderit sequi est et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
