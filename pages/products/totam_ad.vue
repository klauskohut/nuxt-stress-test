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
      return {"slug":"totam_ad","name":"Atque voluptatem dicta voluptatem.","description":"Necessitatibus eos sed. Ut quasi non. Repellat rem aut.","price":11066.49,"header":"Cupiditate nisi fugit ut.","footer":"Aut soluta porro enim.","moreInfo":"Consequatur sint reprehenderit asperiores."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
