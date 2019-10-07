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
      return {"slug":"non-officiis","name":"Labore error reprehenderit iure.","description":"Dolorum totam est. Dolorem dolores vero. Labore sapiente dolore.","price":80934.41,"header":"Ratione nemo quia modi.","footer":"Consequuntur voluptate ducimus sunt.","moreInfo":"Nostrum occaecati rerum et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
