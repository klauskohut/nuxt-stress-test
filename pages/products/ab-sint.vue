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
      return {"slug":"ab-sint","name":"Nesciunt voluptate ipsam qui.","description":"Quibusdam quia iusto. Placeat est numquam. Cupiditate doloribus quas.","price":48790.81,"header":"Accusamus quia aperiam pariatur.","footer":"Blanditiis porro quam aut.","moreInfo":"Doloribus qui non quae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
