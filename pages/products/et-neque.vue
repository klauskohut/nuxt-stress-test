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
      return {"slug":"et-neque","name":"Enim nemo quo sed.","description":"Modi dolores quis. Eum consequatur ipsa. Rem libero et.","price":61190.71,"header":"Deserunt est aut officiis.","footer":"Similique perspiciatis earum placeat.","moreInfo":"Non omnis omnis dolore."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
