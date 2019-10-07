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
      return {"slug":"deleniti_aut","name":"Non error omnis repudiandae.","description":"Quas voluptas quod. In deserunt qui. Ut sapiente ullam.","price":98120.65,"header":"Quaerat sint cum numquam.","footer":"Explicabo eveniet non qui.","moreInfo":"Neque delectus quam recusandae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
