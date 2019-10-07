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
      return {"slug":"quisquam_deleniti","name":"Quidem nisi et facilis.","description":"Non consectetur numquam. Ea dolor voluptas. Expedita nihil odio.","price":92182.87,"header":"Corrupti laboriosam doloremque harum.","footer":"Exercitationem aut alias quia.","moreInfo":"Odit quae vero id."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
