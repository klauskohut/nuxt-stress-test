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
      return {"slug":"error-totam","name":"Sit cumque natus eveniet.","description":"Voluptates ipsum sapiente. Veritatis dolor perferendis. Laborum sint debitis.","price":75846.33,"header":"Quaerat quas tempore quia.","footer":"Sed et voluptatum consequatur.","moreInfo":"Voluptas quam corrupti rerum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
