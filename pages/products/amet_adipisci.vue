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
      return {"slug":"amet_adipisci","name":"Et repudiandae fugit quas.","description":"Commodi soluta iusto. Praesentium suscipit vel. Occaecati alias consequatur.","price":76462.08,"header":"Autem quisquam enim nobis.","footer":"Quia eos eum asperiores.","moreInfo":"Recusandae inventore consequatur atque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
