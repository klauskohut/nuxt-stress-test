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
      return {"slug":"quia_exercitationem","name":"Non sint consequatur eum.","description":"Incidunt omnis totam. Qui ipsum culpa. Fugit quis eveniet.","price":21637.51,"header":"Ut odio aut assumenda.","footer":"Libero et aut praesentium.","moreInfo":"Beatae exercitationem in tempore."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
