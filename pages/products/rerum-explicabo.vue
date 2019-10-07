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
      return {"slug":"rerum-explicabo","name":"Eligendi itaque dolore tenetur.","description":"Quam molestias ullam. Quam ab id. Libero veritatis est.","price":39884.14,"header":"Consequatur deleniti tempore dolorem.","footer":"Placeat dignissimos sunt maiores.","moreInfo":"Quaerat nostrum eos id."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
