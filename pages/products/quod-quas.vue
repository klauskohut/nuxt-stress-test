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
      return {"slug":"quod-quas","name":"Nostrum omnis commodi voluptatibus.","description":"Cupiditate atque adipisci. Aliquam ipsam aspernatur. Laborum distinctio aut.","price":76563.62,"header":"Facere ut dolores qui.","footer":"Culpa inventore quis tenetur.","moreInfo":"Explicabo molestias voluptatem recusandae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
