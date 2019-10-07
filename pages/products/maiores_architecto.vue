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
      return {"slug":"maiores_architecto","name":"Quia ducimus accusantium quisquam.","description":"Libero officia est. Et velit sit. Reiciendis esse soluta.","price":27246.56,"header":"Illo ab optio aut.","footer":"Natus quia cupiditate accusamus.","moreInfo":"Asperiores qui ad ducimus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
