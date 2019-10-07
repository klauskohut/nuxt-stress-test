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
      return {"slug":"sequi_ea","name":"Maiores optio corporis sit.","description":"Tempora eum debitis. Alias quibusdam qui. Fuga alias dicta.","price":25201.87,"header":"Sint a ut dolor.","footer":"Placeat ab omnis vel.","moreInfo":"Sequi eum itaque at."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
