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
      return {"slug":"quod-et","name":"Corrupti ex cumque eum.","description":"Esse porro eveniet. Doloremque eum suscipit. Sed consequatur qui.","price":43604.18,"header":"Sit ad aut quidem.","footer":"Repudiandae culpa dolores eius.","moreInfo":"Voluptas quos illum voluptas."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
