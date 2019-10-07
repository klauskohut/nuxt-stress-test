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
      return {"slug":"rerum-et","name":"Quidem tempora ipsam magnam.","description":"Voluptates quis dolor. Et doloremque explicabo. Quia unde est.","price":50141.55,"header":"Amet id non et.","footer":"Magni dolor suscipit inventore.","moreInfo":"Porro laboriosam est sint."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
