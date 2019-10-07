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
      return {"slug":"et-ea","name":"Et sunt distinctio id.","description":"Qui qui aut. Quisquam facere accusantium. Assumenda iure dolorem.","price":61853.78,"header":"Ea dolores omnis qui.","footer":"Consequatur cumque fuga expedita.","moreInfo":"Delectus reprehenderit quo eos."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
