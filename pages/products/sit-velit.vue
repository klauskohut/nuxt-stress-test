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
      return {"slug":"sit-velit","name":"Illum nisi asperiores maxime.","description":"Qui reiciendis non. Numquam voluptas qui. Delectus qui quia.","price":63730.06,"header":"Mollitia nesciunt voluptatem alias.","footer":"Velit ut quos vitae.","moreInfo":"Voluptatibus temporibus nostrum nesciunt."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
