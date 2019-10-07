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
      return {"slug":"esse-quod","name":"Accusamus vel qui ipsam.","description":"Corrupti est quia. Facere eos vel. Consequatur dolorum velit.","price":21272.17,"header":"Similique vero quaerat deleniti.","footer":"Quibusdam eos quos voluptatibus.","moreInfo":"Quia eveniet velit atque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
