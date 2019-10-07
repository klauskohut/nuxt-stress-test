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
      return {"slug":"eveniet_esse","name":"Hic necessitatibus omnis et.","description":"Harum architecto quia. Cupiditate beatae perspiciatis. Sed aut voluptatem.","price":34115.33,"header":"Blanditiis totam et vitae.","footer":"Tempora quidem doloribus ipsa.","moreInfo":"Ut quia vero adipisci."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
