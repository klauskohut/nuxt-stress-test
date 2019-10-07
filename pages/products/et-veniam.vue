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
      return {"slug":"et-veniam","name":"Velit error atque exercitationem.","description":"Aliquam possimus numquam. Non commodi perspiciatis. Consequatur voluptatem quia.","price":10290.97,"header":"Impedit beatae non voluptatem.","footer":"Quia accusantium ipsa et.","moreInfo":"Aut ex sit provident."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
