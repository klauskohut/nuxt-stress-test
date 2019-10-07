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
      return {"slug":"dolor_id","name":"Non et est et.","description":"Dolor itaque est. Qui voluptatem autem. Nihil laboriosam dolorem.","price":21896.22,"header":"Dolores repellendus quia consequatur.","footer":"Maiores tempora sint corrupti.","moreInfo":"Consequatur totam inventore laudantium."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
