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
      return {"slug":"quisquam_laudantium","name":"Pariatur a id iusto.","description":"Eligendi iusto optio. A atque nihil. Alias est cupiditate.","price":73003.18,"header":"Ad amet suscipit similique.","footer":"Aut fuga omnis excepturi.","moreInfo":"Voluptates nemo dolores eos."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
