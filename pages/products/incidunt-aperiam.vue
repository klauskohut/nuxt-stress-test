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
      return {"slug":"incidunt-aperiam","name":"Rem qui ut aperiam.","description":"Porro quis deleniti. Et aut tenetur. Ut et sint.","price":36355.96,"header":"Labore illum itaque eaque.","footer":"Accusantium sequi nulla at.","moreInfo":"Sit consectetur ut placeat."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
