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
      return {"slug":"eius_aut","name":"Aut non at atque.","description":"Eum est esse. Illum iure cumque. Quo non itaque.","price":51713.15,"header":"Ea praesentium nemo ipsam.","footer":"Aut quia doloribus necessitatibus.","moreInfo":"Neque non adipisci incidunt."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
