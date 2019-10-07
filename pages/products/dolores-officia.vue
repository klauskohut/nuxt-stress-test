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
      return {"slug":"dolores-officia","name":"Reprehenderit expedita vel quasi.","description":"Ea magni qui. Excepturi ipsa est. Blanditiis ex incidunt.","price":60006.29,"header":"Voluptates aperiam sapiente culpa.","footer":"Laboriosam voluptas delectus quo.","moreInfo":"Et et quos dolor."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
