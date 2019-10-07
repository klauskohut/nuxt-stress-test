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
      return {"slug":"quisquam-nobis","name":"Aut vel qui aliquam.","description":"Facilis ipsum sint. Animi sit excepturi. Laudantium quia quaerat.","price":59039.77,"header":"Assumenda enim rem est.","footer":"Aut dicta neque dolores.","moreInfo":"Ab ipsam sapiente ex."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
