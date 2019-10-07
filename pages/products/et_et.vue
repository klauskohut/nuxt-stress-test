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
      return {"slug":"et_et","name":"Rerum error omnis voluptatum.","description":"Ut alias molestiae. Asperiores fuga voluptatibus. Quas veritatis aperiam.","price":56901.07,"header":"Nihil nostrum debitis esse.","footer":"Qui expedita qui rerum.","moreInfo":"Et omnis a rerum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
