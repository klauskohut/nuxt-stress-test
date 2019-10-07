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
      return {"slug":"exercitationem_veritatis","name":"Amet saepe consectetur ratione.","description":"Ex qui nulla. Qui ut sequi. Dolorum autem iste.","price":19014.99,"header":"Delectus et numquam sit.","footer":"Velit sunt harum voluptatem.","moreInfo":"Saepe ut asperiores maiores."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
