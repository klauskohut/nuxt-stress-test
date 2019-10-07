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
      return {"slug":"in-quo","name":"Pariatur reprehenderit eum libero.","description":"Aut voluptates natus. Eligendi et illo. Quibusdam enim magnam.","price":16699.59,"header":"Qui esse nihil qui.","footer":"Dicta non deleniti labore.","moreInfo":"Iste eum et ut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
