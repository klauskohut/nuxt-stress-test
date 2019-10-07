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
      return {"slug":"in-aliquid","name":"Veniam qui consequuntur minima.","description":"Nihil labore dolorem. Porro voluptates delectus. Sed voluptatem mollitia.","price":15401.55,"header":"Qui tempore et ea.","footer":"Sed officia dolor libero.","moreInfo":"Impedit qui voluptates consequuntur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
