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
      return {"slug":"sint_et","name":"Quos ea tenetur est.","description":"Aut ut iure. Et distinctio explicabo. Similique rerum saepe.","price":62130.22,"header":"Vero non odio tempore.","footer":"Possimus quidem unde sunt.","moreInfo":"Fuga fugit quas perferendis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
