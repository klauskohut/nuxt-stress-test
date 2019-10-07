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
      return {"slug":"quidem_occaecati","name":"Et delectus sequi ipsam.","description":"Est et dolor. Adipisci magnam molestiae. Expedita numquam illo.","price":20988.06,"header":"Hic tenetur magni perspiciatis.","footer":"Fuga in labore qui.","moreInfo":"Assumenda amet esse et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
