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
      return {"slug":"libero-aliquid","name":"Modi voluptate aut dignissimos.","description":"Totam quibusdam qui. Voluptates eveniet veritatis. Corrupti vero voluptatem.","price":55960.59,"header":"Animi voluptatem est molestias.","footer":"Molestias porro molestiae deserunt.","moreInfo":"Aut dolorem eveniet qui."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
