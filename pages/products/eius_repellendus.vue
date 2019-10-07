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
      return {"slug":"eius_repellendus","name":"Qui ex amet alias.","description":"Vel eligendi repellat. Repellat praesentium dolore. Aut sed perferendis.","price":71634.17,"header":"Corporis consectetur facere maiores.","footer":"Ut veniam et neque.","moreInfo":"Porro qui molestiae harum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
