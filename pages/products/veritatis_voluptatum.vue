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
      return {"slug":"veritatis_voluptatum","name":"Delectus totam molestias quia.","description":"Quisquam sapiente velit. Eveniet laborum dolor. Minima quia fugit.","price":24249.66,"header":"Nam minus ducimus velit.","footer":"Aperiam quam totam consectetur.","moreInfo":"Quos eum dolorum est."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
