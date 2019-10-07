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
      return {"slug":"rerum-est","name":"Laboriosam ab commodi autem.","description":"Voluptates libero minima. Minima tempora labore. Est nihil ullam.","price":67319.32,"header":"Odit non quas similique.","footer":"Voluptate hic quibusdam impedit.","moreInfo":"Corporis nobis quo nesciunt."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
