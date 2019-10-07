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
      return {"slug":"voluptates_voluptatem","name":"Unde ea adipisci aut.","description":"Molestias maiores iusto. Exercitationem dolorem omnis. Ut et dolor.","price":26346.04,"header":"Est voluptatibus omnis quaerat.","footer":"Sint dolorem qui nam.","moreInfo":"Corporis tempore ad facilis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
