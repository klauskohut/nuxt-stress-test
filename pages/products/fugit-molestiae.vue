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
      return {"slug":"fugit-molestiae","name":"Nihil illo porro sed.","description":"In id saepe. Tenetur vitae quos. Et praesentium odit.","price":27875.69,"header":"Rerum laudantium voluptates sint.","footer":"Ad ut voluptatum est.","moreInfo":"Officiis a repellat voluptatem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
