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
      return {"slug":"impedit_quaerat","name":"Odit animi eius et.","description":"Qui voluptatem exercitationem. Repellendus minima fugit. Nobis iusto dolores.","price":23922.19,"header":"Natus officiis expedita quos.","footer":"Recusandae labore animi pariatur.","moreInfo":"Molestiae quia id facilis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
