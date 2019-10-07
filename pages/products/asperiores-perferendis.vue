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
      return {"slug":"asperiores-perferendis","name":"Explicabo beatae consequatur minima.","description":"Vero non beatae. Nesciunt nemo quia. Quae aspernatur natus.","price":63241.55,"header":"Possimus consequatur accusamus qui.","footer":"Ut voluptatem ullam placeat.","moreInfo":"Temporibus dolorem non nemo."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
