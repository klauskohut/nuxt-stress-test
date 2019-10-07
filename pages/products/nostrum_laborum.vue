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
      return {"slug":"nostrum_laborum","name":"Ipsum velit blanditiis aut.","description":"Ex aut est. Ea quidem quod. Nesciunt facere at.","price":22599.73,"header":"Nulla illum harum iusto.","footer":"Ab quo quidem officia.","moreInfo":"Sit quia excepturi voluptas."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
