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
      return {"slug":"fugit_eaque","name":"Sunt ut omnis odit.","description":"Dolor architecto sequi. Modi beatae voluptates. Aut necessitatibus est.","price":44759.29,"header":"Eum assumenda qui nihil.","footer":"Necessitatibus suscipit est quibusdam.","moreInfo":"Ad non cum nesciunt."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
