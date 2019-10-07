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
      return {"slug":"ut-omnis","name":"Quaerat accusantium placeat modi.","description":"Magni magnam voluptatem. Dicta mollitia porro. Molestias iure consequuntur.","price":36672.61,"header":"Eaque expedita quibusdam distinctio.","footer":"Culpa aspernatur suscipit perferendis.","moreInfo":"Aut accusamus veniam explicabo."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
