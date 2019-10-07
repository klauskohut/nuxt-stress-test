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
      return {"slug":"ex_magni","name":"Nihil voluptas alias odit.","description":"Consequatur minima expedita. Reiciendis iure magni. Sit omnis aut.","price":42421.84,"header":"Est occaecati qui consequuntur.","footer":"Hic sint ut enim.","moreInfo":"Ea pariatur ratione voluptas."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
