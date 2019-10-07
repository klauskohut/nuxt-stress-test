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
      return {"slug":"reprehenderit_vel","name":"Suscipit distinctio excepturi cum.","description":"Et dolor dignissimos. Veniam quaerat cum. Eius qui voluptates.","price":93385.32,"header":"Voluptate autem culpa velit.","footer":"Excepturi ut eos voluptatem.","moreInfo":"Quo sapiente laudantium harum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
