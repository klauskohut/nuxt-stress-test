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
      return {"slug":"aut_facilis","name":"Alias sed mollitia ipsa.","description":"Soluta quo quas. Commodi adipisci placeat. Nobis sint dolorem.","price":55328.46,"header":"Dignissimos eum voluptate ad.","footer":"Omnis eius reiciendis dignissimos.","moreInfo":"Dolorum nisi quos quia."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
