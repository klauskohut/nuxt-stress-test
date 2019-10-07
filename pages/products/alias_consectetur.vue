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
      return {"slug":"alias_consectetur","name":"Dolorum facere rerum incidunt.","description":"Maxime odit quidem. Fugiat dolor adipisci. Est modi et.","price":36297.46,"header":"Aspernatur itaque saepe qui.","footer":"Consequatur distinctio voluptatem culpa.","moreInfo":"A ab delectus voluptatem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
