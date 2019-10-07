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
      return {"slug":"dolorem-eum","name":"Delectus enim enim aut.","description":"Ea iste neque. Quo et odit. Esse sed eos.","price":26320.69,"header":"Facere molestiae cumque non.","footer":"Debitis quia dolorem veniam.","moreInfo":"Cumque reiciendis dolorem vero."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
