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
      return {"slug":"adipisci_magnam","name":"Ipsum voluptas aspernatur sit.","description":"Eos corporis sunt. Exercitationem quia maiores. At deleniti minima.","price":68672.33,"header":"Nemo laborum ducimus blanditiis.","footer":"Qui et saepe eos.","moreInfo":"Pariatur omnis sit delectus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
