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
      return {"slug":"et_recusandae","name":"Labore et ex minus.","description":"Voluptates fuga quas. Qui ut blanditiis. Et qui sint.","price":13817.09,"header":"Qui eos sed nesciunt.","footer":"Quasi facere totam voluptatem.","moreInfo":"Mollitia voluptatem quod illum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
