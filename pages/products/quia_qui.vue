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
      return {"slug":"quia_qui","name":"Nostrum quae ullam eligendi.","description":"Quidem aut numquam. Illo ut sequi. Aut voluptatem alias.","price":10994.22,"header":"Libero suscipit doloribus nesciunt.","footer":"Ab temporibus facilis est.","moreInfo":"Accusamus et iusto neque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
