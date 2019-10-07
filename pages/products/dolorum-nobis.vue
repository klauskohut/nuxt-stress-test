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
      return {"slug":"dolorum-nobis","name":"Exercitationem laborum consequatur ex.","description":"Itaque nobis eveniet. Labore dolor aut. Quia delectus explicabo.","price":73855.46,"header":"Cumque similique qui expedita.","footer":"Autem aut aut quibusdam.","moreInfo":"Doloremque sapiente nihil aut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
