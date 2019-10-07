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
      return {"slug":"quas_minima","name":"Magnam ipsum sed et.","description":"Natus ipsum consequatur. Expedita illo at. Voluptatem quae unde.","price":65890.03,"header":"Ducimus nihil velit rem.","footer":"Inventore officiis at odio.","moreInfo":"Fuga est porro ipsum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
