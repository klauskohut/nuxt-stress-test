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
      return {"slug":"optio-aliquam","name":"Qui sit illum nostrum.","description":"Et voluptate iure. Dolor voluptatem neque. Qui nemo rerum.","price":42432.18,"header":"Nisi ab cumque quidem.","footer":"Doloremque rerum autem deleniti.","moreInfo":"Corrupti eos incidunt deleniti."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
