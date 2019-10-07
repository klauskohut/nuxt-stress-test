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
      return {"slug":"labore-blanditiis","name":"Et voluptatibus quis reiciendis.","description":"Sunt eaque ex. Aut nihil dolore. Aut adipisci qui.","price":87700.98,"header":"Atque minus sunt laborum.","footer":"Eum occaecati laboriosam ipsa.","moreInfo":"Fugiat sint omnis nostrum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
