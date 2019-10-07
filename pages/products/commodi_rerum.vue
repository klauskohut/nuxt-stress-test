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
      return {"slug":"commodi_rerum","name":"Laudantium enim libero aut.","description":"Delectus quia qui. Qui dignissimos fugiat. Nam et impedit.","price":32292.24,"header":"Cumque molestiae nostrum quia.","footer":"Itaque temporibus et asperiores.","moreInfo":"Ut culpa sit veniam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
