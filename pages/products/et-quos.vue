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
      return {"slug":"et-quos","name":"Voluptate harum possimus illo.","description":"Consequatur inventore non. Non architecto consequatur. Rerum vel dolorem.","price":43214.38,"header":"Ut ut enim labore.","footer":"Magni aliquam et quia.","moreInfo":"Rerum est eius illo."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
