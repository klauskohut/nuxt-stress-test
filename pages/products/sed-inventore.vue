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
      return {"slug":"sed-inventore","name":"Et asperiores dolorum deleniti.","description":"Voluptatem quia iure. Amet pariatur illum. Eveniet accusantium sint.","price":82374.55,"header":"Explicabo et omnis consectetur.","footer":"Harum sequi praesentium et.","moreInfo":"Et ad dignissimos voluptates."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
