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
      return {"slug":"minus_modi","name":"Non recusandae est inventore.","description":"Expedita eos nihil. Aut numquam corporis. Et libero aut.","price":64882.68,"header":"Ex quis iusto fuga.","footer":"Debitis sapiente quos suscipit.","moreInfo":"Sequi aliquam nihil ut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
