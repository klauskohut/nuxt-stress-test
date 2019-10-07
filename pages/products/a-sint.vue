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
      return {"slug":"a-sint","name":"Natus est earum et.","description":"Quidem ipsam necessitatibus. Corporis quia ut. Itaque dolorem accusamus.","price":18351.89,"header":"Et ad ea at.","footer":"Et corrupti ut ducimus.","moreInfo":"Iusto ipsa eius iste."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
