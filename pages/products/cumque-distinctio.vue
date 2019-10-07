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
      return {"slug":"cumque-distinctio","name":"Aut culpa id temporibus.","description":"Quas alias ratione. Aut et id. Qui vero mollitia.","price":95620.93,"header":"Dolores illo et maiores.","footer":"Voluptatem id ratione aut.","moreInfo":"Beatae id quo quos."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
