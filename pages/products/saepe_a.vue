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
      return {"slug":"saepe_a","name":"Maxime ut tempore eligendi.","description":"Officiis iste nisi. Neque adipisci aspernatur. Dolorum aperiam accusamus.","price":91206.36,"header":"Sunt ut eligendi magnam.","footer":"Alias esse hic occaecati.","moreInfo":"Ex voluptatem vel adipisci."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
