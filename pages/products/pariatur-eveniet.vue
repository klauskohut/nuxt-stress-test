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
      return {"slug":"pariatur-eveniet","name":"Cum ipsum ut maiores.","description":"Voluptas hic eos. Nemo reprehenderit nulla. Dicta vero temporibus.","price":49972.85,"header":"Reprehenderit ullam incidunt rerum.","footer":"Amet quam hic placeat.","moreInfo":"Recusandae officiis totam laborum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
