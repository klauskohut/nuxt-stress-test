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
      return {"slug":"earum_et","name":"Voluptatem ullam quo quia.","description":"Ex quod ab. Minima libero dicta. Ea in eum.","price":46498.46,"header":"Unde reiciendis atque aperiam.","footer":"Perferendis incidunt dolorum aperiam.","moreInfo":"Non facilis eum aut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
