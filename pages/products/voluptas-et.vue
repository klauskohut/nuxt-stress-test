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
      return {"slug":"voluptas-et","name":"Non repellendus ducimus inventore.","description":"Rem minima expedita. Totam dicta expedita. Voluptatem et reprehenderit.","price":15923.13,"header":"Harum amet minus et.","footer":"Qui illum consequatur nulla.","moreInfo":"Enim incidunt error voluptate."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
