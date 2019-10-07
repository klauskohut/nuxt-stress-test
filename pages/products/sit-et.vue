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
      return {"slug":"sit-et","name":"Ea est aut voluptas.","description":"Reprehenderit aut voluptatem. Facilis eveniet est. Eos fuga quam.","price":22812.72,"header":"Consequatur tempore cum a.","footer":"Dolorum quisquam et qui.","moreInfo":"Officia officiis a vitae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
