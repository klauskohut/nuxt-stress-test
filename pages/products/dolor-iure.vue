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
      return {"slug":"dolor-iure","name":"Amet deleniti labore ducimus.","description":"Perspiciatis cumque perferendis. Ut nemo eos. Consequatur consequuntur corrupti.","price":54526.44,"header":"Odit dolor amet aut.","footer":"Eligendi optio sunt quo.","moreInfo":"Veritatis vel quia sequi."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
