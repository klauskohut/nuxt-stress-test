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
      return {"slug":"est_corrupti","name":"Impedit exercitationem et doloribus.","description":"Sit voluptatibus maiores. Sit dolores quasi. Reiciendis ut quos.","price":68376.98,"header":"Enim alias illum sit.","footer":"Magnam laboriosam aut velit.","moreInfo":"Eos inventore ea velit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
