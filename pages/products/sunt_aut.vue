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
      return {"slug":"sunt_aut","name":"Laboriosam voluptatem aut quia.","description":"Quos nulla fugit. Sed id culpa. Reprehenderit odit et.","price":16070.21,"header":"Rerum et non provident.","footer":"Ex rerum et similique.","moreInfo":"Repellat aut accusantium repellendus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
