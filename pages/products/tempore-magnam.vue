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
      return {"slug":"tempore-magnam","name":"Quis totam consequatur perspiciatis.","description":"Vero iste deserunt. Eius modi omnis. Rerum modi dolores.","price":19193.21,"header":"Dolores autem est quod.","footer":"Veniam minima maxime error.","moreInfo":"Aliquam sunt nisi laboriosam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
