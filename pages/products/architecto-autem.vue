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
      return {"slug":"architecto-autem","name":"Repudiandae tempore dolorum qui.","description":"Ut non sed. Deserunt quos perspiciatis. Molestiae illum dignissimos.","price":85970.79,"header":"Modi aspernatur eos quo.","footer":"Incidunt id commodi omnis.","moreInfo":"Dolor aperiam deserunt consequatur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
