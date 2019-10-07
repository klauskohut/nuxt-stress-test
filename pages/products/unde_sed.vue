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
      return {"slug":"unde_sed","name":"Iusto facere id corrupti.","description":"Magnam ipsam labore. Debitis non voluptatem. Quaerat velit eaque.","price":35672.46,"header":"Culpa aut voluptas iste.","footer":"Qui veritatis et praesentium.","moreInfo":"Maxime vel odit et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
