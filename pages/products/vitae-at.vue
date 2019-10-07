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
      return {"slug":"vitae-at","name":"Earum vel illo dolore.","description":"Similique non nam. Harum tempora amet. Sed voluptatem illo.","price":76965.64,"header":"Est alias autem laudantium.","footer":"Ut quis ut voluptatem.","moreInfo":"Eum iusto porro veritatis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
