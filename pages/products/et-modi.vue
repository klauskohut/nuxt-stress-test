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
      return {"slug":"et-modi","name":"Animi est quod quo.","description":"Quos magnam eos. Et harum quisquam. Totam et dicta.","price":51067.22,"header":"Incidunt ad id rem.","footer":"Voluptatem velit quas autem.","moreInfo":"Temporibus dicta nostrum non."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
