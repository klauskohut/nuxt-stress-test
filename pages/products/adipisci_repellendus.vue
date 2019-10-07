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
      return {"slug":"adipisci_repellendus","name":"Doloremque qui enim consequuntur.","description":"Voluptatem ex quas. Rerum possimus eligendi. Ratione est nihil.","price":34309.12,"header":"Sunt enim at recusandae.","footer":"Quam nihil incidunt corporis.","moreInfo":"Impedit nisi aliquam itaque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
