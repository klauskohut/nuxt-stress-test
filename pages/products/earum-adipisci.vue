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
      return {"slug":"earum-adipisci","name":"Molestiae a in modi.","description":"Adipisci cumque beatae. Molestiae saepe quo. Ad culpa veniam.","price":36892.61,"header":"Ratione tenetur est quis.","footer":"Officiis qui quisquam sunt.","moreInfo":"Alias perferendis nulla rem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
