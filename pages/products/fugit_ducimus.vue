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
      return {"slug":"fugit_ducimus","name":"Provident dolorum dignissimos fugiat.","description":"Eius optio quae. Quam quis ullam. Magni dolor voluptate.","price":72947.92,"header":"Quo dignissimos inventore sed.","footer":"Aut neque atque voluptatem.","moreInfo":"Qui vero et iste."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
