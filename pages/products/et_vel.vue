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
      return {"slug":"et_vel","name":"Debitis omnis ab qui.","description":"Ullam velit qui. Exercitationem omnis veniam. Doloremque aut ut.","price":89578.87,"header":"Et non magni fugit.","footer":"Vitae ipsa ut culpa.","moreInfo":"Similique autem ad architecto."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
