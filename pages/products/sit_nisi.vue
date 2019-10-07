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
      return {"slug":"sit_nisi","name":"Voluptatum laudantium quae ea.","description":"Commodi iusto impedit. Voluptas omnis dolor. Sapiente natus officia.","price":16918.64,"header":"Consequatur ad provident quos.","footer":"Illo error dolore quia.","moreInfo":"Omnis molestiae velit qui."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
