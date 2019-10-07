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
      return {"slug":"recusandae-qui","name":"Illo vero explicabo sint.","description":"Tenetur modi enim. Architecto est commodi. Molestias vel perferendis.","price":29473.46,"header":"Rerum voluptatem sit inventore.","footer":"Nulla debitis ut et.","moreInfo":"Consequatur qui qui minima."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
