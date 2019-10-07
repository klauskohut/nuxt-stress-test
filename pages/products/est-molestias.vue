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
      return {"slug":"est-molestias","name":"Aliquam consequatur sunt illo.","description":"Maiores quisquam voluptas. Modi deserunt illum. Enim dolorum modi.","price":17267.88,"header":"Consequatur sit eos assumenda.","footer":"Nobis numquam minima dolor.","moreInfo":"Fugiat atque sit ea."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
