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
      return {"slug":"delectus_in","name":"Tempora aspernatur aut soluta.","description":"Dolor eos aut. Voluptatum quo molestias. Eaque assumenda sint.","price":75276.34,"header":"Sed distinctio ratione explicabo.","footer":"Est ipsam impedit et.","moreInfo":"Temporibus quia sit distinctio."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
