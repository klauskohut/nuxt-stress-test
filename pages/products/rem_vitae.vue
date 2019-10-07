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
      return {"slug":"rem_vitae","name":"Sit et voluptas temporibus.","description":"Quo ab quo. Excepturi officia ut. Nemo voluptas itaque.","price":13964.44,"header":"Provident nesciunt et repellat.","footer":"Qui quas non aut.","moreInfo":"Rerum sed omnis quia."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
