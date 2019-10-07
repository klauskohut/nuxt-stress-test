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
      return {"slug":"laudantium-facilis","name":"Modi aut voluptatem mollitia.","description":"Laboriosam commodi ipsa. Impedit ipsum consequatur. Quo ad adipisci.","price":26321.57,"header":"Repellendus blanditiis aliquam eos.","footer":"Illum explicabo voluptatibus hic.","moreInfo":"Beatae aut enim autem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
