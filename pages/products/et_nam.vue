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
      return {"slug":"et_nam","name":"Quia aut et perspiciatis.","description":"Nostrum ut sunt. Occaecati minima qui. Et voluptate quod.","price":50000.46,"header":"Est et vitae occaecati.","footer":"Sit dolor ut ipsam.","moreInfo":"Minima sit qui rerum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
