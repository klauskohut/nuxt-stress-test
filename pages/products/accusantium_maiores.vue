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
      return {"slug":"accusantium_maiores","name":"Asperiores dignissimos reiciendis natus.","description":"Alias dolorem vitae. Eos fugiat ut. Consequatur quos nobis.","price":10378.23,"header":"Debitis soluta magnam ut.","footer":"Vel sunt debitis accusamus.","moreInfo":"Error veniam fugiat ipsam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
