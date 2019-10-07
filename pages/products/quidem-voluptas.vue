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
      return {"slug":"quidem-voluptas","name":"Dignissimos quibusdam sit fugiat.","description":"At ullam architecto. Repudiandae debitis deleniti. Ut exercitationem rerum.","price":64250.41,"header":"Ea iure odit similique.","footer":"Magni est reprehenderit delectus.","moreInfo":"Ut ex temporibus sit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
