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
      return {"slug":"ut_natus","name":"Facere dolor porro qui.","description":"Voluptas rem adipisci. Qui enim atque. Totam expedita et.","price":49873.69,"header":"Et quae quis numquam.","footer":"Doloremque delectus harum accusamus.","moreInfo":"Quaerat amet quibusdam voluptas."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
