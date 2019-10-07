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
      return {"slug":"omnis-assumenda","name":"Aut excepturi explicabo ad.","description":"Occaecati architecto error. Voluptatem sunt cumque. At labore ratione.","price":74088.73,"header":"Non atque quo quia.","footer":"Consequatur a nesciunt explicabo.","moreInfo":"Sed dolore dicta quas."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
