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
      return {"slug":"facilis-omnis","name":"Id temporibus voluptas dolore.","description":"Voluptatibus dolorem eaque. Provident at molestias. Quaerat sed id.","price":96731.43,"header":"Et qui aspernatur deserunt.","footer":"Ullam quo voluptatem animi.","moreInfo":"Exercitationem ex eos id."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
