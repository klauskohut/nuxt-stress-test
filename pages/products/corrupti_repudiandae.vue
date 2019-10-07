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
      return {"slug":"corrupti_repudiandae","name":"Eligendi et dolorem quae.","description":"Modi tempore aliquid. Ipsum earum qui. Ipsum id iure.","price":32668.25,"header":"Voluptates saepe unde ea.","footer":"Beatae possimus dignissimos et.","moreInfo":"Enim ut qui molestias."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
