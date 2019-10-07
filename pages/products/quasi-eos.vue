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
      return {"slug":"quasi-eos","name":"Quos exercitationem est quia.","description":"Saepe eius aspernatur. Atque earum aut. Esse non autem.","price":18564.46,"header":"Eos vel molestiae esse.","footer":"Quo ad mollitia ex.","moreInfo":"Deleniti ducimus aliquid distinctio."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
