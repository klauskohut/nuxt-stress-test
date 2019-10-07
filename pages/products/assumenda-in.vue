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
      return {"slug":"assumenda-in","name":"Ullam alias odio commodi.","description":"Id est reprehenderit. Et quisquam enim. Omnis molestiae voluptates.","price":97431.97,"header":"Laboriosam quisquam laborum et.","footer":"Sunt aliquam perferendis aut.","moreInfo":"Quibusdam non in non."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
