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
      return {"slug":"saepe-corporis","name":"Doloribus est ut culpa.","description":"Omnis sint voluptate. Eos aliquam ab. Dignissimos et a.","price":35260.14,"header":"Eligendi doloribus molestiae ut.","footer":"Suscipit quia harum debitis.","moreInfo":"Corporis nihil qui sed."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
