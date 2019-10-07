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
      return {"slug":"blanditiis-sint","name":"Ducimus rerum assumenda est.","description":"Accusamus adipisci quasi. Blanditiis maxime perspiciatis. Totam pariatur corrupti.","price":11836.32,"header":"Dolorem voluptates et perspiciatis.","footer":"Nostrum commodi non aut.","moreInfo":"Unde nisi ad ut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
