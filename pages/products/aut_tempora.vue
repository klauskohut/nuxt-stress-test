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
      return {"slug":"aut_tempora","name":"Omnis officiis quisquam non.","description":"Cum optio molestias. Et id non. Blanditiis unde nesciunt.","price":69543.42,"header":"Dicta repudiandae et ducimus.","footer":"Consequatur quod sequi dolorem.","moreInfo":"Neque similique velit aut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
