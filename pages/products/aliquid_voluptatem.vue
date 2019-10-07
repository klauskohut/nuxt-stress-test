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
      return {"slug":"aliquid_voluptatem","name":"Beatae fuga dicta in.","description":"Voluptatem dignissimos at. Cupiditate a recusandae. Sunt numquam autem.","price":88574.31,"header":"Quasi quod ut sit.","footer":"Assumenda facere sed ipsa.","moreInfo":"Est reiciendis et quaerat."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
