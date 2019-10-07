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
      return {"slug":"rerum-eveniet","name":"Dolor qui consequatur non.","description":"Neque molestiae id. Architecto ullam ipsa. Laudantium sit quis.","price":19603.98,"header":"Inventore velit consequuntur dolore.","footer":"Sed aut dolores minima.","moreInfo":"Dolor doloribus ipsum ratione."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
