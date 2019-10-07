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
      return {"slug":"veritatis-ut","name":"Rerum eum consequuntur aut.","description":"Dolor est enim. Consequatur ea delectus. Doloribus qui unde.","price":88279.62,"header":"Hic doloribus sint illum.","footer":"Deleniti eos corporis rem.","moreInfo":"Sapiente iure ad qui."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
