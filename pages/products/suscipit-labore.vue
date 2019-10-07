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
      return {"slug":"suscipit-labore","name":"Nesciunt asperiores suscipit fugit.","description":"Error id atque. Sint quia optio. Provident harum unde.","price":79378.19,"header":"Vel dolorem officiis odit.","footer":"Sint impedit sed deserunt.","moreInfo":"Iusto quod aperiam sint."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
