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
      return {"slug":"odio-explicabo","name":"Est quisquam at enim.","description":"Nemo et aut. Possimus voluptas aut. Hic voluptas sequi.","price":21601.18,"header":"Facere ratione est voluptatum.","footer":"Dolor est eius et.","moreInfo":"Veritatis reprehenderit quas non."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
