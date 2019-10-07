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
      return {"slug":"sunt_beatae","name":"Natus distinctio ea corporis.","description":"Quod maiores quaerat. Optio doloremque quisquam. Voluptas sed enim.","price":46001.83,"header":"Ipsam nam et officia.","footer":"Totam repellendus facilis quo.","moreInfo":"Velit ducimus labore cumque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
