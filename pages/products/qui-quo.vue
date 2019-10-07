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
      return {"slug":"qui-quo","name":"Dolor ea est aut.","description":"Omnis et molestiae. Vel fugit corporis. Deleniti ad officiis.","price":73309.31,"header":"Itaque consectetur fugit nostrum.","footer":"Iusto nemo nam minus.","moreInfo":"At assumenda recusandae tempora."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
