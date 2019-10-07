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
      return {"slug":"est-ducimus","name":"Tenetur iure aut accusamus.","description":"Minima sit eos. Quos officiis distinctio. Rerum voluptatibus quia.","price":92111.18,"header":"Veniam dolores voluptate voluptatum.","footer":"Et veniam hic voluptatem.","moreInfo":"Autem eius delectus perferendis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
