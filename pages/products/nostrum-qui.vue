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
      return {"slug":"nostrum-qui","name":"Hic qui sunt velit.","description":"Corporis odio vel. Sint nulla commodi. Iure velit minus.","price":29747.27,"header":"Magnam nemo occaecati fugiat.","footer":"Ea accusamus dolorem voluptatibus.","moreInfo":"Et est sed quia."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
