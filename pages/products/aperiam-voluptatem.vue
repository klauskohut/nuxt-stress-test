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
      return {"slug":"aperiam-voluptatem","name":"Nobis omnis aliquid consequuntur.","description":"Possimus cum delectus. Velit autem nihil. Beatae aut est.","price":80456.45,"header":"Vitae ea nobis commodi.","footer":"Aut natus saepe aut.","moreInfo":"Mollitia dicta et repellendus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
