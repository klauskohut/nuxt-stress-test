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
      return {"slug":"nemo_doloremque","name":"Ab tempore expedita pariatur.","description":"Saepe esse vel. Soluta quia voluptas. Delectus nam molestias.","price":13360.38,"header":"Voluptatem nemo sed laudantium.","footer":"Asperiores ut laudantium iusto.","moreInfo":"Exercitationem necessitatibus enim voluptate."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
