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
      return {"slug":"pariatur_aspernatur","name":"Officia ea est nesciunt.","description":"Excepturi est voluptates. Ut odit voluptatem. Minima velit odit.","price":71992.74,"header":"Accusamus quis sunt nam.","footer":"Accusamus dolores autem dicta.","moreInfo":"Aut soluta adipisci enim."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
