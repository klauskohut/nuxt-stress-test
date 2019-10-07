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
      return {"slug":"vitae-ut","name":"Ut libero earum ab.","description":"Voluptatem corrupti ab. Rerum ipsam perferendis. Commodi eligendi molestiae.","price":21368.72,"header":"Ut exercitationem nesciunt dolor.","footer":"Labore natus quae earum.","moreInfo":"Atque sed quam consequatur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
