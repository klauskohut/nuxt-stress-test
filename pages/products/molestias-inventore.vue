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
      return {"slug":"molestias-inventore","name":"Qui voluptas et voluptatem.","description":"Labore ducimus blanditiis. Voluptates aut debitis. Architecto exercitationem doloremque.","price":40268.65,"header":"Ratione unde vel sunt.","footer":"Quasi vel quo reprehenderit.","moreInfo":"Et provident magnam error."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
