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
      return {"slug":"necessitatibus-quasi","name":"Et corrupti sit quo.","description":"Voluptas recusandae veniam. Facere atque doloribus. Ipsam natus non.","price":61676.09,"header":"Dolorem commodi necessitatibus minima.","footer":"Enim molestiae ducimus totam.","moreInfo":"Aliquam quod natus aut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
