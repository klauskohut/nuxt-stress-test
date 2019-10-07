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
      return {"slug":"eum-consequatur","name":"Dolorum libero aspernatur dolor.","description":"Cupiditate dolores dignissimos. Omnis quo praesentium. Voluptatibus esse nisi.","price":80232.68,"header":"Rem aliquam perferendis quaerat.","footer":"Impedit minima cum nisi.","moreInfo":"Sit voluptatem neque inventore."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
