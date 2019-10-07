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
      return {"slug":"non_eligendi","name":"Doloremque accusantium commodi sapiente.","description":"Sunt in corrupti. Sit sapiente sed. Eos inventore ut.","price":18835.73,"header":"Sapiente nihil cumque aut.","footer":"Quisquam autem officiis quam.","moreInfo":"Voluptatem fuga soluta aspernatur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
