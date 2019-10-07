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
      return {"slug":"a_sit","name":"Ab dolores aut nihil.","description":"Ipsum qui est. Quam et quia. Explicabo eius rerum.","price":61860.59,"header":"In deleniti itaque doloribus.","footer":"Accusamus ut aut dolorem.","moreInfo":"Repudiandae veniam aut illum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
