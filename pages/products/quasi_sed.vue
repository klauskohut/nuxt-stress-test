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
      return {"slug":"quasi_sed","name":"Qui odio quia exercitationem.","description":"Neque quos nisi. Corrupti tenetur facere. Accusamus molestias blanditiis.","price":12353.89,"header":"Tempora eos in et.","footer":"Error doloribus labore eum.","moreInfo":"Ipsa sit aut rerum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
