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
      return {"slug":"reprehenderit_et","name":"Eveniet incidunt corrupti dolorem.","description":"Optio accusamus dicta. Quia et consequatur. Qui omnis numquam.","price":96245.84,"header":"Ut sunt commodi laudantium.","footer":"Cum magni quae accusantium.","moreInfo":"Eaque et et et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
