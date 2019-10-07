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
      return {"slug":"eos-a","name":"Maiores et illum suscipit.","description":"Veniam et similique. Et cupiditate rerum. Ut voluptas nostrum.","price":65530.97,"header":"Sit velit commodi ut.","footer":"Dolorem maxime quia quis.","moreInfo":"Dolorum tenetur ipsam provident."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
