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
      return {"slug":"nihil-ipsa","name":"Alias eligendi veniam ut.","description":"Eum consequatur iste. Eos provident alias. Neque non voluptatem.","price":94658.13,"header":"Quo illo ipsa atque.","footer":"Rem ut temporibus nobis.","moreInfo":"Sunt corrupti voluptatibus dolor."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
