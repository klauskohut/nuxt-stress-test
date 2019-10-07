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
      return {"slug":"debitis_voluptatem","name":"Fugiat omnis eos omnis.","description":"Nihil at necessitatibus. Adipisci odit illum. Dignissimos harum nisi.","price":36680.21,"header":"Nesciunt fugit laborum cumque.","footer":"Quas rerum earum est.","moreInfo":"Sint fuga ducimus rerum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
