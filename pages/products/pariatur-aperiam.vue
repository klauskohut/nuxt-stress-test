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
      return {"slug":"pariatur-aperiam","name":"Eum dignissimos delectus nostrum.","description":"Culpa omnis perspiciatis. In unde necessitatibus. Qui totam eos.","price":34078.92,"header":"Id illum vel eaque.","footer":"Distinctio pariatur iste sunt.","moreInfo":"Sed repellendus aut ratione."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
