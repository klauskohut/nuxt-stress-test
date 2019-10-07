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
      return {"slug":"iste_ut","name":"Non distinctio amet dolores.","description":"Quibusdam quis sapiente. Enim magnam occaecati. Iure omnis doloribus.","price":10038.73,"header":"Nesciunt optio velit placeat.","footer":"Aut voluptas autem sapiente.","moreInfo":"Est vel inventore aut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
