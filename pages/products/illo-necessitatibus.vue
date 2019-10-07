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
      return {"slug":"illo-necessitatibus","name":"Est accusantium delectus rerum.","description":"Qui est eum. Earum aliquam consequuntur. Voluptatem excepturi et.","price":84481.41,"header":"Et voluptatem accusantium recusandae.","footer":"Quis sapiente voluptatem aliquid.","moreInfo":"Atque facilis delectus quo."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
