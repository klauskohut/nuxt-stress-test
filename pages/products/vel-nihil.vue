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
      return {"slug":"vel-nihil","name":"Porro et in sapiente.","description":"Voluptas officiis quasi. Consequuntur repudiandae sunt. Labore iure rerum.","price":50098.76,"header":"A esse eaque quas.","footer":"Suscipit ea ab omnis.","moreInfo":"Voluptas occaecati iste sed."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
