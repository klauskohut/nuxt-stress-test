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
      return {"slug":"possimus-assumenda","name":"Eveniet mollitia accusamus magni.","description":"Accusantium ea eum. Rem voluptate minus. Quis quod sunt.","price":59775.37,"header":"Commodi quo est quo.","footer":"Cupiditate et assumenda dolores.","moreInfo":"Eos qui odit ullam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
