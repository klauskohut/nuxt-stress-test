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
      return {"slug":"voluptatum_necessitatibus","name":"Autem reprehenderit et tempora.","description":"Odio dolore quo. Quia laborum corrupti. Maiores impedit sit.","price":68399.57,"header":"Exercitationem et repudiandae adipisci.","footer":"Sed sit impedit doloremque.","moreInfo":"Consectetur dolor eveniet odit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
