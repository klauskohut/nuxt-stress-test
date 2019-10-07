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
      return {"slug":"eligendi-sequi","name":"Id voluptatem laudantium suscipit.","description":"Ratione eius non. Mollitia sint sapiente. Delectus ut aut.","price":61668.19,"header":"Soluta delectus minima sit.","footer":"Dolores modi tempora quo.","moreInfo":"Ipsam quia quibusdam illum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
