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
      return {"slug":"id-nostrum","name":"Laboriosam ut quidem id.","description":"Molestiae et ut. Doloremque ipsa qui. Dolorum consequatur aut.","price":90813.95,"header":"Est aut nisi aut.","footer":"Sit ut sed quia.","moreInfo":"Porro provident aliquid optio."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
