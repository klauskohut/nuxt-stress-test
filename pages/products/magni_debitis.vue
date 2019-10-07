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
      return {"slug":"magni_debitis","name":"Maiores hic suscipit enim.","description":"Aut sapiente eius. Rerum quam rerum. Eum sed fugiat.","price":81242.03,"header":"Rerum facilis qui et.","footer":"Debitis hic ducimus minima.","moreInfo":"Atque molestiae quae est."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
