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
      return {"slug":"architecto-numquam","name":"Molestiae et autem facere.","description":"Dolorum debitis et. Sit voluptas soluta. Ullam nobis autem.","price":61316.47,"header":"Accusantium veritatis officiis et.","footer":"Aliquid rerum corporis occaecati.","moreInfo":"Et sint ad voluptate."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
