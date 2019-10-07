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
      return {"slug":"aut_odio","name":"Ad officiis error ut.","description":"Minus est assumenda. Vel deleniti laboriosam. Necessitatibus sunt deserunt.","price":25861.25,"header":"Est temporibus molestiae beatae.","footer":"Sed illum alias velit.","moreInfo":"Laborum sequi quod sint."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
