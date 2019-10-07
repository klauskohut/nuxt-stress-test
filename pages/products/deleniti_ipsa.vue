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
      return {"slug":"deleniti_ipsa","name":"Rem quasi blanditiis ex.","description":"Vel quod quia. Id mollitia cupiditate. Est natus aut.","price":14222.54,"header":"Doloremque officia et iste.","footer":"Adipisci ullam saepe ad.","moreInfo":"Necessitatibus cum distinctio dolorem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
