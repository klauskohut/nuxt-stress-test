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
      return {"slug":"iste-pariatur","name":"Quisquam et voluptatem commodi.","description":"Quis id laboriosam. Quia eligendi quo. Expedita earum neque.","price":32854.63,"header":"Beatae non ullam cum.","footer":"Ut autem at et.","moreInfo":"Vel repellendus sit est."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
