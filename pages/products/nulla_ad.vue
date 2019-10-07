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
      return {"slug":"nulla_ad","name":"Aspernatur et vitae ducimus.","description":"Ipsa sint debitis. Possimus cumque qui. Ut modi voluptatibus.","price":81125.52,"header":"Labore et rem veritatis.","footer":"Ipsam sit delectus cum.","moreInfo":"Possimus aliquid alias voluptas."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
