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
      return {"slug":"incidunt_sit","name":"Eos et et commodi.","description":"Ut est hic. In dignissimos temporibus. Distinctio est vitae.","price":17368.62,"header":"Suscipit nemo quam et.","footer":"Beatae illum at similique.","moreInfo":"Iste sunt qui aut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
