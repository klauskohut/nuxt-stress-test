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
      return {"slug":"est_assumenda","name":"Voluptas excepturi cum consequuntur.","description":"Error possimus et. Quaerat expedita tenetur. Eum quae laudantium.","price":99700.79,"header":"Ut qui consequatur et.","footer":"Nesciunt eligendi at recusandae.","moreInfo":"Hic sint eos et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
