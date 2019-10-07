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
      return {"slug":"consequatur_officiis","name":"Est tempora et et.","description":"Sint ut sit. Laboriosam modi est. Consequatur fuga quos.","price":30406.42,"header":"Quia ipsam esse culpa.","footer":"Quaerat adipisci officia nihil.","moreInfo":"Ullam ex maxime officiis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
