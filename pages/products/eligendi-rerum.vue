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
      return {"slug":"eligendi-rerum","name":"Harum ex aut ut.","description":"Blanditiis repellendus aut. Aspernatur cumque aut. Temporibus corrupti ipsa.","price":39133.15,"header":"Exercitationem omnis et adipisci.","footer":"Provident aliquam illum ea.","moreInfo":"Aut quasi porro explicabo."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
