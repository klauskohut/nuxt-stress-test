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
      return {"slug":"et_quis","name":"Praesentium voluptatum voluptas corporis.","description":"Sed veritatis ut. Consequuntur inventore assumenda. Est omnis odio.","price":33737.45,"header":"Magnam deserunt sit quis.","footer":"Repellendus facere modi quis.","moreInfo":"Placeat cumque nesciunt ipsum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
