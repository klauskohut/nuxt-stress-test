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
      return {"slug":"atque_quo","name":"Accusantium veniam assumenda qui.","description":"Dolorem asperiores ipsam. Ut esse error. Necessitatibus vitae minima.","price":59409.63,"header":"Alias consectetur ipsa voluptates.","footer":"Reprehenderit voluptas sit animi.","moreInfo":"Molestiae ducimus consequatur quaerat."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
