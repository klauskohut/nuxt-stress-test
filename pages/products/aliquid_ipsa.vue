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
      return {"slug":"aliquid_ipsa","name":"Sit aut dolores quibusdam.","description":"Optio quisquam nisi. Atque aperiam tempora. Sequi soluta consequuntur.","price":23797.84,"header":"Iure consequatur ut itaque.","footer":"Omnis qui quis quaerat.","moreInfo":"Eos illum eum voluptatum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
