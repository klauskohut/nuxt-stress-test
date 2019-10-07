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
      return {"slug":"quia-perspiciatis","name":"Soluta necessitatibus ut delectus.","description":"Autem dignissimos omnis. Consectetur ipsam voluptatem. Esse quia reiciendis.","price":83434.34,"header":"Nihil necessitatibus molestias ab.","footer":"Libero et et fugit.","moreInfo":"Et consequatur sit fugiat."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
