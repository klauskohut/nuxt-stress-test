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
      return {"slug":"officia-in","name":"Incidunt placeat voluptatibus labore.","description":"Natus minima tempora. Omnis fugiat ratione. Libero veniam ut.","price":85653.83,"header":"Quia totam similique fuga.","footer":"Autem et est qui.","moreInfo":"Qui vero quae nobis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
