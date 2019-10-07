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
      return {"slug":"architecto-at","name":"Impedit eum et deleniti.","description":"Veniam illo minus. Ea iste vero. Reprehenderit qui cum.","price":26051.95,"header":"Aut quae minus maxime.","footer":"Repellat porro voluptates exercitationem.","moreInfo":"Nulla id id est."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
