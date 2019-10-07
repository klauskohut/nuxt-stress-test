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
      return {"slug":"eum-velit","name":"Qui tempora consequatur ut.","description":"At consectetur non. Et dolorum minima. Ullam ab enim.","price":30163.78,"header":"At perferendis rem accusamus.","footer":"Aut eaque corrupti ad.","moreInfo":"Et vitae neque autem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
