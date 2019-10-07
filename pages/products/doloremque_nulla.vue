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
      return {"slug":"doloremque_nulla","name":"Voluptatem in quod voluptate.","description":"Et accusamus suscipit. Iusto voluptatem excepturi. Magni fugiat aliquid.","price":83677.02,"header":"Quaerat totam nesciunt et.","footer":"Adipisci corporis expedita illum.","moreInfo":"Nostrum qui neque culpa."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
