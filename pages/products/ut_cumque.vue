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
      return {"slug":"ut_cumque","name":"Et esse dolor perspiciatis.","description":"Qui rem recusandae. Quia maiores nisi. Distinctio cum ullam.","price":47293.22,"header":"Quia nostrum qui corporis.","footer":"Et consequatur veniam labore.","moreInfo":"Animi voluptas qui cumque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
