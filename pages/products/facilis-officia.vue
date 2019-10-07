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
      return {"slug":"facilis-officia","name":"Aperiam est quasi et.","description":"Alias autem laborum. Aut ad similique. Quod laboriosam est.","price":34157.19,"header":"In dolor praesentium illo.","footer":"Quidem at qui soluta.","moreInfo":"Magni molestiae in facere."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
