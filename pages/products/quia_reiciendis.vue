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
      return {"slug":"quia_reiciendis","name":"Voluptatem aut officiis vel.","description":"Aut dicta tenetur. Autem ut dolores. Ut voluptatibus ea.","price":82091.71,"header":"Sequi dicta natus repellat.","footer":"Ut sint omnis aliquam.","moreInfo":"Amet facilis rem quia."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
