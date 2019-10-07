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
      return {"slug":"voluptas-quas","name":"Sint quaerat aut quis.","description":"Voluptatibus dolorum ut. Occaecati nesciunt qui. Harum consequatur molestiae.","price":22615.18,"header":"Qui distinctio et ullam.","footer":"Pariatur nihil animi doloribus.","moreInfo":"Molestiae ut quae voluptas."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
