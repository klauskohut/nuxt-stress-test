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
      return {"slug":"maiores_similique","name":"Ea velit iure recusandae.","description":"Esse ducimus aut. Totam deleniti qui. Enim vero rerum.","price":58234.49,"header":"Earum exercitationem repellendus sequi.","footer":"Reiciendis laboriosam repellendus a.","moreInfo":"At dolores libero voluptas."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
