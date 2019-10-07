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
      return {"slug":"asperiores_rerum","name":"Quia beatae numquam iusto.","description":"Rerum nihil ullam. Velit voluptate consequatur. Itaque aliquid nesciunt.","price":11841.45,"header":"Corrupti incidunt modi est.","footer":"Consequatur temporibus voluptate iste.","moreInfo":"Voluptate accusantium eveniet nam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
