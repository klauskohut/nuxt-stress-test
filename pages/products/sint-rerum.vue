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
      return {"slug":"sint-rerum","name":"Quo id dolores et.","description":"Quae aliquid ipsam. Vitae est inventore. Aut odio expedita.","price":16030.14,"header":"Eaque soluta dolore perferendis.","footer":"Voluptatem voluptate nulla autem.","moreInfo":"Quo praesentium impedit ut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
