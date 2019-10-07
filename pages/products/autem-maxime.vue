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
      return {"slug":"autem-maxime","name":"Ullam doloremque recusandae qui.","description":"Et aliquid rem. Iure et ut. Odio labore repellat.","price":37197.76,"header":"Occaecati aliquid itaque magni.","footer":"Earum ut est temporibus.","moreInfo":"Veniam quo fugiat ut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
