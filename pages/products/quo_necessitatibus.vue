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
      return {"slug":"quo_necessitatibus","name":"Quasi quibusdam vitae asperiores.","description":"Numquam ut laborum. Est quasi a. Dolores repellendus ipsum.","price":69298.07,"header":"Ut soluta voluptatem sunt.","footer":"Voluptas eius eos ea.","moreInfo":"Nulla debitis qui et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
