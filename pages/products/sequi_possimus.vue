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
      return {"slug":"sequi_possimus","name":"Saepe illo ab et.","description":"Ut sequi pariatur. Amet voluptas eos. Nemo sit vel.","price":43524.05,"header":"Nulla id voluptates rerum.","footer":"Optio illum assumenda officia.","moreInfo":"Perferendis est cupiditate nostrum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
