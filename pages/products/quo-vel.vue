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
      return {"slug":"quo-vel","name":"Iure eos ex facilis.","description":"Neque odio placeat. Rerum voluptas qui. Ea voluptatem maxime.","price":29058.17,"header":"Voluptatem quos sed occaecati.","footer":"Blanditiis dolores enim accusamus.","moreInfo":"Quas officia similique est."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
