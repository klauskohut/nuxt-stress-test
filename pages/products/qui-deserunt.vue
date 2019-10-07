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
      return {"slug":"qui-deserunt","name":"Nisi beatae impedit ut.","description":"Architecto perspiciatis quos. Asperiores iure ea. Iste doloremque ut.","price":51555.25,"header":"Facilis sed modi rem.","footer":"Nesciunt ea quod non.","moreInfo":"Alias consequatur adipisci nihil."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
