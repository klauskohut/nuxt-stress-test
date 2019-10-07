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
      return {"slug":"similique-commodi","name":"Officia reprehenderit soluta mollitia.","description":"Possimus veritatis quos. Amet aperiam eum. Rerum quam nihil.","price":14343.13,"header":"Est impedit est cupiditate.","footer":"Nam velit dolor quia.","moreInfo":"Optio nihil quo velit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
