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
      return {"slug":"consectetur_fuga","name":"Illum quod non molestias.","description":"Autem enim omnis. Rerum est error. Dolorum temporibus quo.","price":49590.75,"header":"Ex dolor fuga voluptatem.","footer":"Optio et omnis odio.","moreInfo":"Error corrupti quos qui."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
