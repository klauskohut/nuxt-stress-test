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
      return {"slug":"qui-et","name":"Atque quibusdam sunt velit.","description":"Iusto voluptatem aut. Explicabo facilis assumenda. Quam facere iste.","price":91694.62,"header":"Est ad quidem corporis.","footer":"Delectus est deleniti voluptas.","moreInfo":"Voluptas laborum eos rem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
