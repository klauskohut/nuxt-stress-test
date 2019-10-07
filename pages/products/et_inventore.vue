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
      return {"slug":"et_inventore","name":"Eveniet hic ipsam voluptates.","description":"Ut voluptate odit. Ad qui dolores. Sit esse est.","price":82227.68,"header":"Et ut accusantium soluta.","footer":"Ut officiis ut quaerat.","moreInfo":"Autem similique quas eius."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
