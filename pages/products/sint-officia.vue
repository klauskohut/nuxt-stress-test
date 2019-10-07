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
      return {"slug":"sint-officia","name":"Nemo consectetur distinctio reiciendis.","description":"Doloribus omnis corrupti. Ducimus ea sint. Est in voluptatibus.","price":16390.65,"header":"Blanditiis enim qui et.","footer":"Quia consectetur velit voluptates.","moreInfo":"Hic doloremque qui quod."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
