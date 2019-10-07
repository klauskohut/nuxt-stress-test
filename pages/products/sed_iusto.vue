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
      return {"slug":"sed_iusto","name":"Aliquid qui fugiat sapiente.","description":"Nihil itaque amet. Aut adipisci ut. Consequatur distinctio nostrum.","price":43167.19,"header":"Et odio fugiat sequi.","footer":"Laudantium provident fugiat excepturi.","moreInfo":"Neque occaecati necessitatibus natus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
