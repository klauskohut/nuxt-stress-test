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
      return {"slug":"quia_rerum","name":"Quos ipsam possimus vel.","description":"Nemo vitae et. Quidem ad vitae. Ea eum ea.","price":90319.87,"header":"Magnam aspernatur architecto repellat.","footer":"Odio nemo nihil temporibus.","moreInfo":"Ut laboriosam earum sapiente."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
