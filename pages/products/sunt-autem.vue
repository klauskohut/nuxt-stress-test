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
      return {"slug":"sunt-autem","name":"Voluptas et facere eos.","description":"Suscipit non debitis. Assumenda blanditiis ut. Iure ipsum itaque.","price":57047.21,"header":"Rem sequi natus et.","footer":"Vel repellendus eum ipsum.","moreInfo":"Consequatur rerum ut animi."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
