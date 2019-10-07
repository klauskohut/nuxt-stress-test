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
      return {"slug":"error_expedita","name":"Alias est iure nemo.","description":"Mollitia rerum saepe. Ut illo expedita. Numquam aut dolorum.","price":81361.84,"header":"Eos corrupti est aut.","footer":"Dolorem earum rerum debitis.","moreInfo":"Eos nemo sed temporibus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
